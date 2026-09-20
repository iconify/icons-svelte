<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-mridb4l.css';
import '../../css/i/inzdek_cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="m-mridb4l"/><path class="inzdek_cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:comments" {...props}></Icon>
