<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwy2peqdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwy2peqdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dots-horizontal" {...props}></Icon>
