<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rouiqnbvi.css';
import '../../css/l/lxa7bxwkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":33};
const content = `<g class="cuyn6tgcc"><path class="rouiqnbvi"/><path class="lxa7bxwkb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:keycap-5" {...props}></Icon>
