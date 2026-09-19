<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/our_mccad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="our_mccad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:jenkins" {...props}></Icon>
