<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhy3x40hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhy3x40hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pavilion-line" {...props}></Icon>
