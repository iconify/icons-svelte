<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fds47bcdd.css';
import '../../css/t/tsmzb05mv.css';
import '../../css/w/wvhc50bir.css';
import '../../css/c/c9-_ko9gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="fds47bcdd"/><path clip-rule="evenodd" class="tsmzb05mv"/><path class="wvhc50bir"/><path class="c9-_ko9gt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:joker-bold" {...props}></Icon>
