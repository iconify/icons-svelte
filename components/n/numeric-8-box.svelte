<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh80lrzhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh80lrzhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-8-box" {...props}></Icon>
