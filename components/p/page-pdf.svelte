<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0cbo8bvk.css';
import '../../css/f/fd4fpfb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="x0cbo8bvk"/><path class="fd4fpfb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-pdf" {...props}></Icon>
