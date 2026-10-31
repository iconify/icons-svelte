<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmcmwabro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmcmwabro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pixelwatch" {...props}></Icon>
