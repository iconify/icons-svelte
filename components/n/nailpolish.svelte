<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8-rrpbya.css';
import '../../css/z/z7_tv0bli.css';
import '../../css/j/ja3silbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="c8-rrpbya"/><path class="z7_tv0bli"/><path class="ja3silbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:nailpolish" {...props}></Icon>
