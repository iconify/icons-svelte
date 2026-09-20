<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu8jyibot.css';
import '../../css/f/fa7sd-bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu8jyibot"/><path class="fa7sd-bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:butterfly-2-line" {...props}></Icon>
