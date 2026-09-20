<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl1fvfbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl1fvfbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-front-glass" {...props}></Icon>
