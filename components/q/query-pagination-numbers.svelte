<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/j_xescbfb.css';
import '../../css/a/a3h_uub7j.css';
import '../../css/n/nnb345baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="j_xescbfb"/><path class="a3h_uub7j"/><path class="nnb345baj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:query-pagination-numbers" {...props}></Icon>
