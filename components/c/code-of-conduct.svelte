<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gej5qbeik.css';
import '../../css/o/oaf-ekb5m.css';
import '../../css/q/qawp00bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="gej5qbeik"><path class="oaf-ekb5m"/><path class="qawp00bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:code-of-conduct" {...props}></Icon>
