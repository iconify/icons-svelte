<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckc0imbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ckc0imbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:interactions" {...props}></Icon>
