<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pwmtrpb8b.css';
import '../../css/f/fix04rbfz.css';
import '../../css/c/c757m7bdq.css';
import '../../css/u/u1ulbtb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pwmtrpb8b"/><ellipse class="fix04rbfz"/><ellipse class="c757m7bdq"/><path clip-rule="evenodd" class="u1ulbtb_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:music-note-double" {...props}></Icon>
