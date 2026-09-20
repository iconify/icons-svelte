<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn1-i_b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn1-i_b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-play" {...props}></Icon>
