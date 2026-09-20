<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdrdz7b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fdrdz7b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:linecap-round-outline" {...props}></Icon>
