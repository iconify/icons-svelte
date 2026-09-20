<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0cf7pyxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0cf7pyxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-traffic" {...props}></Icon>
