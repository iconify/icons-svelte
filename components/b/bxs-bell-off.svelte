<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmw53x3_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmw53x3_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bell-off" {...props}></Icon>
