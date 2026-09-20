<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj4m-lvhg.css';
import '../../css/a/a0xu55but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj4m-lvhg"/><path class="a0xu55but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:base-station-2-line" {...props}></Icon>
