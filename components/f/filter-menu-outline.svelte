<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_p8a8bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_p8a8bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filter-menu-outline" {...props}></Icon>
