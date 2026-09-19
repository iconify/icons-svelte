<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcbn25zhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="xcbn25zhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:desktop" {...props}></Icon>
