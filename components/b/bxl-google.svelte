<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6k1i1bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6k1i1bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-google" {...props}></Icon>
