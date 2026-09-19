<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e25xsfz0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="e25xsfz0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:eraser" {...props}></Icon>
