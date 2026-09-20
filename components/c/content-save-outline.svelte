<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db3x8nb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db3x8nb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-outline" {...props}></Icon>
