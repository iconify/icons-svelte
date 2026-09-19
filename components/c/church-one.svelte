<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/cslsnsbdo.css';
import '../../css/d/daj4drb4a.css';
import '../../css/j/j9hg1or3h.css';
import '../../css/h/hh_ficcty.css';
import '../../css/t/tt3n4ibfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="cslsnsbdo"/><path class="daj4drb4a"/><path class="j9hg1or3h"/><path class="hh_ficcty"/><path class="tt3n4ibfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:church-one" {...props}></Icon>
