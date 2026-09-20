<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2on09xws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2on09xws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-clock-outline" {...props}></Icon>
