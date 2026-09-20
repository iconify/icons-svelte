<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn3w0p46b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn3w0p46b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:blinds-horizontal-closed" {...props}></Icon>
