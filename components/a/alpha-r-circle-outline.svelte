<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo-lowbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo-lowbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-r-circle-outline" {...props}></Icon>
