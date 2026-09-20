<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r01dfskhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r01dfskhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:eye" {...props}></Icon>
