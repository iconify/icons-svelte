<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epqu04bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epqu04bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:crop-rotate" {...props}></Icon>
