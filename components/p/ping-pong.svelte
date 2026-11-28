<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyau2rryt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyau2rryt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ping-pong" {...props}></Icon>
