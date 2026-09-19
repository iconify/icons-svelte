<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ig6egccad.css';
import '../../css/s/s5kl10b-b.css';
import '../../css/u/u721mxb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ig6egccad"/><path class="s5kl10b-b"/><path clip-rule="evenodd" class="u721mxb4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mosquito-collection-negative" {...props}></Icon>
