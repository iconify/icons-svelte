<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/s/sfubw46ew.css';
import '../../css/x/xl7_gdfrs.css';
import '../../css/i/iljijccvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="h01tyzbfu"><path class="sfubw46ew"/><path class="xl7_gdfrs"/><circle transform="rotate(-45 6.95 7.38)" class="iljijccvp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:label-print" {...props}></Icon>
