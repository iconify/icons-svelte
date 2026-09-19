<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdfr1w_pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdfr1w_pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-dock-top" {...props}></Icon>
