<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei7bin-rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ei7bin-rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:netlogo" {...props}></Icon>
