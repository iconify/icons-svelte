<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz6gwxb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jz6gwxb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:high-speed-train" {...props}></Icon>
