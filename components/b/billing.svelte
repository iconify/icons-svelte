<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upkyg_b6q.css';
import '../../css/f/fz7rrmbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="upkyg_b6q"/><path class="fz7rrmbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:billing" {...props}></Icon>
