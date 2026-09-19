<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rapo_tbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2208,"height":1664};
const content = `<path class="rapo_tbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:multi-arrow" {...props}></Icon>
