<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdq7f1w4s.css';
import '../../css/k/kbhx_-s8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdq7f1w4s"/><path class="kbhx_-s8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:power-button-bold" {...props}></Icon>
