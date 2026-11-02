<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg8ifwz8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg8ifwz8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-heart-line" {...props}></Icon>
