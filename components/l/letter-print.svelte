<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n9zc5cbms.css';
import '../../css/r/r4hbm720t.css';
import '../../css/a/anypatboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="n9zc5cbms"/><path clip-rule="evenodd" class="r4hbm720t"/><path clip-rule="evenodd" class="anypatboj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:letter-print" {...props}></Icon>
