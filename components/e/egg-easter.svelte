<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrvj_fbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrvj_fbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:egg-easter" {...props}></Icon>
