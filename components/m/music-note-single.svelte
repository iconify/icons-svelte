<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/odxuk-bkc.css';
import '../../css/j/jwclepbql.css';
import '../../css/y/yh1nqihsf.css';
import '../../css/m/mxs3jyekp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="odxuk-bkc"/><path clip-rule="evenodd" class="jwclepbql"/><path class="yh1nqihsf"/><path clip-rule="evenodd" class="mxs3jyekp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:music-note-single" {...props}></Icon>
