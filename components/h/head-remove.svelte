<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkm46bb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkm46bb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-remove" {...props}></Icon>
