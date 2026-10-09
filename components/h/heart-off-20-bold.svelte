<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li-550_tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="li-550_tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-off-20-bold" {...props}></Icon>
