<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-quszbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i-quszbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-quantum-safe-explorer" {...props}></Icon>
