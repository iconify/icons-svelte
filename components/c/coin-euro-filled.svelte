<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_hrlfu3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_hrlfu3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:coin-euro-filled" {...props}></Icon>
