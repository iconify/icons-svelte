<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy092wb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy092wb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-slider" {...props}></Icon>
