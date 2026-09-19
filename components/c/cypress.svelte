<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfttfe_2y.css';
import '../../css/l/leakr4_1e.css';
import '../../css/f/fudu618jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="leakr4_1e"/><path class="fudu618jx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:cypress" {...props}></Icon>
