<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhu-10bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhu-10bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pound-sterling-solid" {...props}></Icon>
