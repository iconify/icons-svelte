<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0q3lubcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n0q3lubcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-stroke-16" {...props}></Icon>
