<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/shsp_xb_i.css';
import '../../css/g/ghb_84b2f.css';
import '../../css/j/jgj6o_1pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="shsp_xb_i"/><path class="ghb_84b2f"/><path class="jgj6o_1pm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:facial-cleanser" {...props}></Icon>
