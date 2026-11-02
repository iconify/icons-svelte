<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8lmxsbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8lmxsbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-share-line" {...props}></Icon>
