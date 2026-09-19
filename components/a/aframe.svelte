<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6j2i1bzb.css';
import '../../css/n/nwa55i2nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f6j2i1bzb"/><path class="nwa55i2nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:aframe" {...props}></Icon>
