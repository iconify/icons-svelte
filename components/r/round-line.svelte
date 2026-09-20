<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1l8t4z4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="u1l8t4z4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:round-line" {...props}></Icon>
