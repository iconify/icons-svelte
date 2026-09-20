<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkc-ohblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zkc-ohblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:packing-box-outline" {...props}></Icon>
