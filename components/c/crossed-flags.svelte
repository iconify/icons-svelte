<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfux_ebdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kfux_ebdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:crossed-flags" {...props}></Icon>
