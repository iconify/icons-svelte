<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na7e-6bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na7e-6bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-ring-outline" {...props}></Icon>
