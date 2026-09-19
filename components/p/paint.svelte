<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgnx6ab5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cgnx6ab5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:paint" {...props}></Icon>
