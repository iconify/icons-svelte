<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mngos4sma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mngos4sma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:netease-cloud-music-line" {...props}></Icon>
