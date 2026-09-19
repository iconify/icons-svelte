<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5himacnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z5himacnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:font" {...props}></Icon>
