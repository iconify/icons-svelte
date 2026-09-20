<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx1s9bc_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx1s9bc_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:notification-2-line" {...props}></Icon>
