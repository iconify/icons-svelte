<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3vmni1om.css';
import '../../css/i/i_h7t1znx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3vmni1om"/><path class="i_h7t1znx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:microchip-board-bold" {...props}></Icon>
