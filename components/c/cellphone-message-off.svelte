<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwa1_bb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwa1_bb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-message-off" {...props}></Icon>
