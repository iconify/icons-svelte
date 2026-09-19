<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxmh49ktf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sxmh49ktf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:icicles" {...props}></Icon>
