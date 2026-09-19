<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/egmt2gfpt.css';
import '../../css/a/ab73cxb4x.css';
import '../../css/j/j6e3-sg1a.css';
import '../../css/c/cb-if1bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="egmt2gfpt"/><path class="ab73cxb4x"/><path class="j6e3-sg1a"/><path class="cb-if1bxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:envelope-open-note-duo" {...props}></Icon>
