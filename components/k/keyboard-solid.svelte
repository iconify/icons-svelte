<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1i1z-bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r1i1z-bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:keyboard-solid" {...props}></Icon>
