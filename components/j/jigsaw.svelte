<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgygppras.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jgygppras"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:jigsaw" {...props}></Icon>
