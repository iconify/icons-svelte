<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsq8u9wdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fsq8u9wdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:pen-to-square" {...props}></Icon>
