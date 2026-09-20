<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utbu3d6ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utbu3d6ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:achievement-variant-outline" {...props}></Icon>
