<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woqxoebsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woqxoebsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:microphone-line" {...props}></Icon>
