<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9ehfkb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9ehfkb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-question-mark-line" {...props}></Icon>
