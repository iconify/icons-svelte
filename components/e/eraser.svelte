<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9cux6ikc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e9cux6ikc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:eraser" {...props}></Icon>
