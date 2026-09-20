<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpujj_1gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpujj_1gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:notebook-remove" {...props}></Icon>
