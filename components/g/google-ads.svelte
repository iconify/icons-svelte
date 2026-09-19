<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jraag1gus.css';
import '../../css/t/tzb2l-bbx.css';
import '../../css/g/g8-jwabbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="jraag1gus"/><path class="tzb2l-bbx"/><circle transform="rotate(25 12.083 36.688)" class="g8-jwabbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:google-ads" {...props}></Icon>
