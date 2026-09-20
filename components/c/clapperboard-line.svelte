<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w39b4_bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w39b4_bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clapperboard-line" {...props}></Icon>
