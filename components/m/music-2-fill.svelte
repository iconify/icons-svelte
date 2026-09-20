<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbmh4p5by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbmh4p5by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:music-2-fill" {...props}></Icon>
