<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnuj16bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pnuj16bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:r" {...props}></Icon>
