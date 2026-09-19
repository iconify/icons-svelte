<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0czi8bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u0czi8bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:onedrive" {...props}></Icon>
