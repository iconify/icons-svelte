<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc3om3dtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wc3om3dtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-point-up" {...props}></Icon>
