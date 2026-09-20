<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdvbgl_hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zdvbgl_hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-down" {...props}></Icon>
