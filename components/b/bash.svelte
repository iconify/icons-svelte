<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfttfe_2y.css';
import '../../css/k/kvn-2v0wt.css';
import '../../css/u/uj7ng7b-o.css';
import '../../css/v/vmxx54baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="kvn-2v0wt"/><path class="uj7ng7b-o"/><path class="vmxx54baz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:bash" {...props}></Icon>
