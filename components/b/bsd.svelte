<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-37kwbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e-37kwbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bsd" {...props}></Icon>
