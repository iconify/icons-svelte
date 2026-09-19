<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxtpt-biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxtpt-biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-popsicle" {...props}></Icon>
