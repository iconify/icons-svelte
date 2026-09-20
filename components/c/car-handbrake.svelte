<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1a-1b7oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1a-1b7oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-handbrake" {...props}></Icon>
