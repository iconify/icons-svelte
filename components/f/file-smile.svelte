<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bk_r3rbbz.css';
import '../../css/d/dyevr4boi.css';
import '../../css/q/qfwattbuf.css';
import '../../css/i/ikzht7pab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bk_r3rbbz"/><path class="dyevr4boi"/><path clip-rule="evenodd" class="qfwattbuf"/><path class="ikzht7pab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:file-smile" {...props}></Icon>
