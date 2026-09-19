<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/du5xobhgo.css';
import '../../css/h/hz2zgmbpt.css';
import '../../css/h/hu_nuxbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="du5xobhgo"/><path class="hz2zgmbpt"/><path class="hu_nuxbxh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:plan" {...props}></Icon>
