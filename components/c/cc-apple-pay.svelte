<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_zvdpf8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j_zvdpf8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:cc-apple-pay" {...props}></Icon>
