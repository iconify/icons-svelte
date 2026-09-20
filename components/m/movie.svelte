<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f73y469bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f73y469bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:movie" {...props}></Icon>
