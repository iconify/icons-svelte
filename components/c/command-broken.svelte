<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/a1quj3bph.css';
import '../../css/w/w_9u0rbob.css';
import '../../css/m/mg9xohbul.css';
import '../../css/y/y8y0m0wuw.css';
import '../../css/l/lf0aqebqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a1quj3bph"/><path class="w_9u0rbob"/><path class="mg9xohbul"/><path class="y8y0m0wuw"/><path class="lf0aqebqg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:command-broken" {...props}></Icon>
