<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bgju2vbae.css';
import '../../css/h/hu6m7zbrv.css';
import '../../css/i/izz9u2a6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="bgju2vbae"/><circle class="hu6m7zbrv"/><path class="izz9u2a6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pearl-of-the-orient" {...props}></Icon>
