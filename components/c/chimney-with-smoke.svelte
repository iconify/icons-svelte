<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co__nwbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="co__nwbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:chimney-with-smoke" {...props}></Icon>
