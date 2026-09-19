<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp24w_8tf.css';
import '../../css/f/f8cpqdg_j.css';
import '../../css/u/ux2lhde9c.css';
import '../../css/t/t-b_8j6mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="sp24w_8tf"><path class="f8cpqdg_j"/><path class="ux2lhde9c"/><path class="t-b_8j6mv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:natural-mode" {...props}></Icon>
