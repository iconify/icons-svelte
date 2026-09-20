<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oulufsb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oulufsb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-cutter-off" {...props}></Icon>
