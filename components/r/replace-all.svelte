<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/ji6u8v2gx.css';
import '../../css/w/w1ei77bwa.css';
import '../../css/p/pebu9abvj.css';
import '../../css/i/io862l57z.css';
import '../../css/o/olnn03mma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ji6u8v2gx"/><path clip-rule="evenodd" class="w1ei77bwa"/><path class="pebu9abvj"/><path clip-rule="evenodd" class="io862l57z"/><path class="olnn03mma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:replace-all" {...props}></Icon>
