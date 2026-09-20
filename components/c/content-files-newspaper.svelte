<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkms2ybtu.css';
import '../../css/f/fw-p8rb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jkms2ybtu"/><path class="fw-p8rb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-newspaper" {...props}></Icon>
