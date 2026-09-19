<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/a/a3622aqmt.css';
import '../../css/d/dl46ut6jf.css';
import '../../css/y/ycgeubb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="a3622aqmt"/><path clip-rule="evenodd" class="dl46ut6jf"/><path class="ycgeubb3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bottle" {...props}></Icon>
