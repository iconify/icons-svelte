<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0xr4npzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d0xr4npzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bacteria" {...props}></Icon>
