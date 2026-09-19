<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqglm8bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vqglm8bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-reverse-continue" {...props}></Icon>
