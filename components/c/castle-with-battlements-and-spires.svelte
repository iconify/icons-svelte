<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9jeykb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m9jeykb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:castle-with-battlements-and-spires" {...props}></Icon>
