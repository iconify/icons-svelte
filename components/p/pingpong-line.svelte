<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dash5mbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dash5mbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pingpong-line" {...props}></Icon>
