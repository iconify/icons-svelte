<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8o3sgtkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q8o3sgtkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-governance-tracked" {...props}></Icon>
