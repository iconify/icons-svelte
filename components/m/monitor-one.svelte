<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iso-sy05t.css';
import '../../css/r/r2_2dlbjg.css';
import '../../css/l/l4y0xgwkr.css';
import '../../css/y/y19va-bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="iso-sy05t"/><path class="r2_2dlbjg"/><circle class="l4y0xgwkr"/><path class="y19va-bzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:monitor-one" {...props}></Icon>
