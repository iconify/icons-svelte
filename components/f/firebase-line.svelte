<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utq87upmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utq87upmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:firebase-line" {...props}></Icon>
