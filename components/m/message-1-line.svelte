<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy-g8lbjc.css';
import '../../css/t/tykix6bve.css';
import '../../css/p/p9m9lkbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy-g8lbjc"/><path class="tykix6bve"/><path class="p9m9lkbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-1-line" {...props}></Icon>
