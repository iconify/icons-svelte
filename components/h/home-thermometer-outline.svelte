<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waxltl5fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waxltl5fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-thermometer-outline" {...props}></Icon>
