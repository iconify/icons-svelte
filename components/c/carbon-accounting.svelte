<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uih3f9bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uih3f9bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:carbon-accounting" {...props}></Icon>
