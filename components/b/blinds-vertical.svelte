<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvc_kgbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvc_kgbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:blinds-vertical" {...props}></Icon>
