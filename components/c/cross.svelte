<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acu85ycbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="acu85ycbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:cross" {...props}></Icon>
