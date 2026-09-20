<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0lf81_ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0lf81_ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:auto-awesome-mosaic" {...props}></Icon>
