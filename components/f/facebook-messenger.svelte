<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf86pn3hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jf86pn3hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:facebook-messenger" {...props}></Icon>
