<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-ttp2b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-ttp2b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ping-pong" {...props}></Icon>
