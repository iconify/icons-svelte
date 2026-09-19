<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1mehsijf.css';
import '../../css/q/qqdio8bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k1mehsijf"/><path class="qqdio8bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:backspace-outline" {...props}></Icon>
