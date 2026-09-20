<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nh6vwjb6k.css';
import '../../css/x/xjeqo6bqe.css';
import '../../css/r/rcf3djyxt.css';
import '../../css/z/zz499ob7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><circle class="nh6vwjb6k"/><path class="xjeqo6bqe"/><path class="rcf3djyxt"/><path class="zz499ob7z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:reload" {...props}></Icon>
