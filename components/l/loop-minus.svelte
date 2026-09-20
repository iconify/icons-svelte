<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h9t3y3buj.css';
import '../../css/o/o8tzs_jpg.css';
import '../../css/b/btpxxkpmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h9t3y3buj"/><path clip-rule="evenodd" class="o8tzs_jpg"/><path class="btpxxkpmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:loop-minus" {...props}></Icon>
