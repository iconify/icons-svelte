<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl6ttu2ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hl6ttu2ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:plane-circle-exclamation" {...props}></Icon>
