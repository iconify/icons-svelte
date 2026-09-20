<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyu5frbjg.css';
import '../../css/z/zt0uakzko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":800};
const content = `<path class="vyu5frbjg"/><path class="zt0uakzko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pi" {...props}></Icon>
