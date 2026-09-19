<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/a3c8mjbsl.css';
import '../../css/i/isvo6rdbz.css';
import '../../css/r/r8f-8remn.css';
import '../../css/d/dbnkfibrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="a3c8mjbsl"/><path class="isvo6rdbz"/><path class="r8f-8remn"/><path class="dbnkfibrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:joker-outline" {...props}></Icon>
