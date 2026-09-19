<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0s1z4bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0s1z4bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-javascript" {...props}></Icon>
