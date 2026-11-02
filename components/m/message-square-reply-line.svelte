<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-9n2pbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-9n2pbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-reply-line" {...props}></Icon>
