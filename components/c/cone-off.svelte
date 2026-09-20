<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqinhgbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqinhgbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cone-off" {...props}></Icon>
