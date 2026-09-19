<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uhprvbkhh.css';
import '../../css/i/ihvftj6_d.css';
import '../../css/f/fgs3gl2sz.css';
import '../../css/j/jiax3zkxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="uhprvbkhh"/><path clip-rule="evenodd" class="ihvftj6_d"/><path class="fgs3gl2sz"/><path clip-rule="evenodd" class="jiax3zkxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:respirator2x-outline" {...props}></Icon>
