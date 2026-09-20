<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gemozpbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gemozpbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-cycle" {...props}></Icon>
