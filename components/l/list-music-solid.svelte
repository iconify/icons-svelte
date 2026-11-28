<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlem3eb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlem3eb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-music-solid" {...props}></Icon>
