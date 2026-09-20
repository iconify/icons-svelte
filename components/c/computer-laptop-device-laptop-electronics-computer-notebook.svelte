<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p01i7hbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="p01i7hbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-laptop-device-laptop-electronics-computer-notebook" {...props}></Icon>
