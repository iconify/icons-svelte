<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tinjsabav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tinjsabav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-monster-horns-gloss" {...props}></Icon>
