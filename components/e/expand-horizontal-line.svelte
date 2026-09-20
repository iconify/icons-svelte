<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbr8r1bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbr8r1bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-horizontal-line" {...props}></Icon>
