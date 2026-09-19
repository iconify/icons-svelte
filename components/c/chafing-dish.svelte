<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/d2rpgdn0m.css';
import '../../css/o/oxj5f2bhb.css';
import '../../css/v/vddxckb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="d2rpgdn0m"/><path class="oxj5f2bhb"/><path class="vddxckb1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:chafing-dish" {...props}></Icon>
