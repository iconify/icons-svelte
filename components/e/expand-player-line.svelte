<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypi1vib0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypi1vib0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:expand-player-line" {...props}></Icon>
