<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hor504bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hor504bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:graph-bell-curve-cumulative" {...props}></Icon>
