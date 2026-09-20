<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygfcqccex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygfcqccex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:paint-brush-fill" {...props}></Icon>
