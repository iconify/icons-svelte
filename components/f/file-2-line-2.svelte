<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf4yk0big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf4yk0big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-2-line-2" {...props}></Icon>
