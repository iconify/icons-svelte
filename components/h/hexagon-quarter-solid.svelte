<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5pb54b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5pb54b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hexagon-quarter-solid" {...props}></Icon>
