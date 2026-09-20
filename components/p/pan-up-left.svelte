<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaj_g9blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaj_g9blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pan-up-left" {...props}></Icon>
