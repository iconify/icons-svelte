<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/j850wac-i.css';
import '../../css/u/u_haqyhvf.css';
import '../../css/z/zrt4urc1f.css';
import '../../css/z/zsrvp_b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="j850wac-i"/><path class="u_haqyhvf"/><circle class="zrt4urc1f"/><circle class="zsrvp_b7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:engineering-vehicle" {...props}></Icon>
