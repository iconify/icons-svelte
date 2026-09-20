<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-26d3blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-26d3blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-two-circle" {...props}></Icon>
