<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbet2ubpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fbet2ubpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:eye-low-vision" {...props}></Icon>
