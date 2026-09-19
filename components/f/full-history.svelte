<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6h4d3bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="t6h4d3bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:full-history" {...props}></Icon>
