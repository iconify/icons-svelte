<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yci3bsb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yci3bsb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:circle-dot" {...props}></Icon>
