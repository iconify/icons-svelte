<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xze6pdbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xze6pdbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:people-pause" {...props}></Icon>
