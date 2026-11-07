<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo3mbbcpz.css';
import '../../css/z/zv6teybjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo3mbbcpz"/><path class="zv6teybjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:revote-outline" {...props}></Icon>
