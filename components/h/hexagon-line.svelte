<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlo3x6s-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlo3x6s-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hexagon-line" {...props}></Icon>
