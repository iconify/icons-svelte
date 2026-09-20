<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocpi9mk0u.css';
import '../../css/v/v031subhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocpi9mk0u"/><path class="v031subhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:desktop-monitor" {...props}></Icon>
