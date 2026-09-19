<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws7o0qx6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ws7o0qx6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:chz" {...props}></Icon>
