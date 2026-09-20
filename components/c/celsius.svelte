<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsg8k7w8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vsg8k7w8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:celsius" {...props}></Icon>
