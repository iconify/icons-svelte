<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncs3bccmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncs3bccmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hexagon-slice-6" {...props}></Icon>
