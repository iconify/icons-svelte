<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy5afrstx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy5afrstx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:basketball" {...props}></Icon>
