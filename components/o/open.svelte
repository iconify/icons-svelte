<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x717t0dsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x717t0dsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:open" {...props}></Icon>
