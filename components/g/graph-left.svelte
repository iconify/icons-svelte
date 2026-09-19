<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvb739bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fvb739bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:graph-left" {...props}></Icon>
