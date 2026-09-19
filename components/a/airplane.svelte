<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np-303tvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="np-303tvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:airplane" {...props}></Icon>
