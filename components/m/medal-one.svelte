<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/w/w-nbvvb-v.css';
import '../../css/n/ngnbouohf.css';
import '../../css/s/stxou8bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="w-nbvvb-v"/><circle class="ngnbouohf"/><circle class="stxou8bht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:medal-one" {...props}></Icon>
