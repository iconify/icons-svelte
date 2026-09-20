<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf6uh2ajn.css';
import '../../css/n/n-w0yccsj.css';
import '../../css/p/pjg6v4bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf6uh2ajn"/><path class="n-w0yccsj"/><path class="pjg6v4bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-2-line" {...props}></Icon>
