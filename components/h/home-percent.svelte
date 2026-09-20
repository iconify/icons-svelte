<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn34ipb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn34ipb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:home-percent" {...props}></Icon>
