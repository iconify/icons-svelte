<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5xaexbmp.css';
import '../../css/r/rp66vlbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g5xaexbmp"/><path class="rp66vlbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:edge-service" {...props}></Icon>
