<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dy8hfib4w.css';
import '../../css/h/h15eclbzw.css';
import '../../css/t/tax1typah.css';
import '../../css/k/kap5sbxvf.css';
import '../../css/h/hxr6trbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dy8hfib4w"/><path class="h15eclbzw"/><path clip-rule="evenodd" class="tax1typah"/><path class="kap5sbxvf"/><path clip-rule="evenodd" class="hxr6trbjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:confetti" {...props}></Icon>
