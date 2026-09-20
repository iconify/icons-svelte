<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iue1-vgbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iue1-vgbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:freemasonry" {...props}></Icon>
