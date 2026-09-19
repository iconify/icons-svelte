<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze9alyjfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ze9alyjfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:dhl" {...props}></Icon>
