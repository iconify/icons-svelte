<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxe0vybfv.css';
import '../../css/c/c6l5vwb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxe0vybfv"/><path class="c6l5vwb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:business-card-hand-2-bold" {...props}></Icon>
