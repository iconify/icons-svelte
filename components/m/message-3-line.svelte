<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy-g8lbjc.css';
import '../../css/i/i99p7sv5h.css';
import '../../css/p/p9m9lkbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy-g8lbjc"/><path class="i99p7sv5h"/><path class="p9m9lkbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-3-line" {...props}></Icon>
