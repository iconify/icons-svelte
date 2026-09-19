<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feg7vxbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="feg7vxbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chess-knight" {...props}></Icon>
