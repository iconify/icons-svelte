<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2ay67glx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2ay67glx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-5-boxes-outline" {...props}></Icon>
