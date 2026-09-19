<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2ce9acfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="a2ce9acfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:angle-double-down" {...props}></Icon>
