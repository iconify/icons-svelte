<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxs9e9bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxs9e9bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:rocket" {...props}></Icon>
