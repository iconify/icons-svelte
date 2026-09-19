<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw_fxrxtk.css';
import '../../css/i/ivfjhjnom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw_fxrxtk"/><path class="ivfjhjnom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:desktop-mouse-2" {...props}></Icon>
