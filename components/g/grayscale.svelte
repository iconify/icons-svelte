<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-9fyzgba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":646};
const content = `<path class="r-9fyzgba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:grayscale" {...props}></Icon>
