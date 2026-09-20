<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5cnq49py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5cnq49py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-shooting-outline" {...props}></Icon>
