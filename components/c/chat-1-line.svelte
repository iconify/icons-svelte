<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qstwzrbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qstwzrbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-1-line" {...props}></Icon>
