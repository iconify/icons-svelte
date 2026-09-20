<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cefw7kb1y.css';
import '../../css/p/pfyahacbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="cefw7kb1y"/><path class="pfyahacbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:left-right-arrow" {...props}></Icon>
