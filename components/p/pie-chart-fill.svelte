<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-07iacxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-07iacxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pie-chart-fill" {...props}></Icon>
