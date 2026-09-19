<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z33gtxdmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z33gtxdmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:blind-tilt-closed" {...props}></Icon>
