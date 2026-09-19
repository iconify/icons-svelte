<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfttfe_2y.css';
import '../../css/x/xwqlguw3x.css';
import '../../css/p/pn1ylfbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="xwqlguw3x"/><path class="pn1ylfbdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:ms-excel" {...props}></Icon>
