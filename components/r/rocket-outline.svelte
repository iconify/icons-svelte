<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnz88h8pe.css';
import '../../css/v/vs_irilvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pnz88h8pe"/><path class="vs_irilvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:rocket-outline" {...props}></Icon>
