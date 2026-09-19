<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dox58tamg.css';
import '../../css/w/w7xqf2bhc.css';
import '../../css/c/cm_b0kbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="dox58tamg"/><path class="w7xqf2bhc"/><circle class="cm_b0kbjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:duck" {...props}></Icon>
