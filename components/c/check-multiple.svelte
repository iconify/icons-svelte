<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt1y1kpfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt1y1kpfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:check-multiple" {...props}></Icon>
