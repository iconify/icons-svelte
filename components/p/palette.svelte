<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sndv11bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sndv11bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:palette" {...props}></Icon>
