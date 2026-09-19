<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdsu42b0b.css';
import '../../css/z/z0-acdc1y.css';
import '../../css/x/x9_6abtpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="jdsu42b0b"/><path class="z0-acdc1y"/><path class="x9_6abtpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-definition" {...props}></Icon>
