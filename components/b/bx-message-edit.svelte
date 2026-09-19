<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvcg5__wh.css';
import '../../css/s/sk589gbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvcg5__wh"/><path class="sk589gbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-message-edit" {...props}></Icon>
