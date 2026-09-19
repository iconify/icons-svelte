<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/l/lnyuaxrwt.css';
import '../../css/t/t69oulbwo.css';
import '../../css/a/az25568cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="lnyuaxrwt"/><path class="t69oulbwo"/><path class="az25568cs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:neural" {...props}></Icon>
