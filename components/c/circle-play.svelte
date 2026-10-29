<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl5uzhbhz.css';
import '../../css/o/ohnjhbbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl5uzhbhz wm-k"/><path class="ohnjhbbiz wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:circle-play" {...props}></Icon>
