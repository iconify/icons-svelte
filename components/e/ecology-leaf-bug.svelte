<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0tgts-yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e0tgts-yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-leaf-bug" {...props}></Icon>
