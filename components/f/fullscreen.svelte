<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtxw-s4kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtxw-s4kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:fullscreen" {...props}></Icon>
