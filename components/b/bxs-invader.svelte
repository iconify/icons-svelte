<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa-mfb10x.css';
import '../../css/d/d5ojkxbdk.css';
import '../../css/b/bot1wzbxy.css';
import '../../css/h/hj9jr80pc.css';
import '../../css/l/lknnxwbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa-mfb10x"/><path class="d5ojkxbdk"/><path class="bot1wzbxy"/><path class="hj9jr80pc"/><path class="lknnxwbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-invader" {...props}></Icon>
