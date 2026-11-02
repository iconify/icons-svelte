<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f74x5-b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f74x5-b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:expand-player-line" {...props}></Icon>
