<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjh5ppb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjh5ppb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hexagon-slice-2" {...props}></Icon>
