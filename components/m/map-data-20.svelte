<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg3i25mms.css';
import '../../css/u/u80q53cnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tg3i25mms"/><path class="u80q53cnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-data-20" {...props}></Icon>
