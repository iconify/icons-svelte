<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k10ze3ubr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k10ze3ubr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-user" {...props}></Icon>
