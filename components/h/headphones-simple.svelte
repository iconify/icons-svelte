<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgcn0ybkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fgcn0ybkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:headphones-simple" {...props}></Icon>
