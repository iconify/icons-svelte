<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy0b-_gxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy0b-_gxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relative-scale" {...props}></Icon>
