<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-_sw2qvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_sw2qvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:modern-tv-curvy-edge-bold" {...props}></Icon>
