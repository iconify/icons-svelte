<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbkxeac3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbkxeac3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-b-circle-outline" {...props}></Icon>
