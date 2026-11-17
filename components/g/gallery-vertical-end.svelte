<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/u/uc7uzkbwa.css';
import '../../css/u/u05znbefx.css';
import '../../css/n/nbimxkbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="uc7uzkbwa"/><path class="u05znbefx"/><path class="nbimxkbcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:gallery-vertical-end" {...props}></Icon>
