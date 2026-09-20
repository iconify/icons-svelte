<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-j23qbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-j23qbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:equalizer-2-line" {...props}></Icon>
