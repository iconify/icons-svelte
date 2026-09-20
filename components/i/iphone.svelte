<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbo7vsg8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fbo7vsg8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:iphone" {...props}></Icon>
