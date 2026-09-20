<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox68djqql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox68djqql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mickeymouse-line" {...props}></Icon>
