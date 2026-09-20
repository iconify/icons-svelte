<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxw-o-_5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxw-o-_5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-h-circle-outline" {...props}></Icon>
