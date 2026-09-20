<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eci9ug11m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eci9ug11m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hight-beam-headlights-line" {...props}></Icon>
