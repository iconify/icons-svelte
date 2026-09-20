<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxkkv7aav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxkkv7aav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-bold-hexagon-outline" {...props}></Icon>
