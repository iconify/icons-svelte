<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rckfhcc4g.css';
import '../../css/u/u0awpynix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rckfhcc4g"/><path class="u0awpynix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:postcard" {...props}></Icon>
