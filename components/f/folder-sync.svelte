<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy7nu5b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy7nu5b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-sync" {...props}></Icon>
