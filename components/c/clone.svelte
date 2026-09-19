<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbrj4gkkb.css';
import '../../css/y/ytbt4-b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wbrj4gkkb"/><path class="ytbt4-b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:clone" {...props}></Icon>
