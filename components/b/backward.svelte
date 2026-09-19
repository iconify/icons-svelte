<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8eg9ma1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i8eg9ma1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:backward" {...props}></Icon>
