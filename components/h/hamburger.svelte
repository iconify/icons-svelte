<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t7oitngpi.css';
import '../../css/h/ho72t4bwy.css';
import '../../css/c/cdzff5bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="t7oitngpi"/><path clip-rule="evenodd" class="ho72t4bwy"/><path class="cdzff5bms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:hamburger" {...props}></Icon>
