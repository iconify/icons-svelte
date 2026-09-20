<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3hr4oboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3hr4oboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:network-strength-alert-outline" {...props}></Icon>
