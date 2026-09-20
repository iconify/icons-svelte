<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcb_rnbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcb_rnbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:color-blind-bold" {...props}></Icon>
