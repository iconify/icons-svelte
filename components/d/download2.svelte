<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0bv6ac3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c0bv6ac3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:download2" {...props}></Icon>
