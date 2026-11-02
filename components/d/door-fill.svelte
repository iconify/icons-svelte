<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd7_f5brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd7_f5brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:door-fill" {...props}></Icon>
