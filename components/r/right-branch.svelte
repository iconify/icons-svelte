<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u5oj9bbnl.css';
import '../../css/w/wn9vp_q7p.css';
import '../../css/h/hpifqdbin.css';
import '../../css/k/kkkqdqbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="u5oj9bbnl"/><path class="wn9vp_q7p"/><circle class="hpifqdbin"/><path class="kkkqdqbde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:right-branch" {...props}></Icon>
