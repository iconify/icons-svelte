<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haqr67bmp.css';
import '../../css/i/iixqn4bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haqr67bmp"/><path class="iixqn4bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-direction-up-line" {...props}></Icon>
