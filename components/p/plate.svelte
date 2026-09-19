<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k--uqqbpr.css';
import '../../css/l/leiq1ib6u.css';
import '../../css/h/hc2a3kmhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="k--uqqbpr"/><circle class="leiq1ib6u"/><circle class="hc2a3kmhy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:plate" {...props}></Icon>
