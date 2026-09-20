<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw2citbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw2citbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:day-temperature" {...props}></Icon>
