<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt7l2dbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qt7l2dbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:proj-stereo" {...props}></Icon>
