<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve418qbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve418qbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:globe-box" {...props}></Icon>
