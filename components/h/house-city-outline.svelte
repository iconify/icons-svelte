<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs3sugevh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs3sugevh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-city-outline" {...props}></Icon>
