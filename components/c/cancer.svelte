<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/dx22jsbgo.css';
import '../../css/p/pgcwh7bgt.css';
import '../../css/c/cvpduvoip.css';
import '../../css/e/errurjr8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="dx22jsbgo"/><path class="pgcwh7bgt"/><circle transform="rotate(-180 11 31)" class="cvpduvoip"/><path class="errurjr8u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cancer" {...props}></Icon>
