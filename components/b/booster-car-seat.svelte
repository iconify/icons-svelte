<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/mbiljzlix.css';
import '../../css/o/o2nmueu5h.css';
import '../../css/p/pswfvabxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="mbiljzlix"/><path class="o2nmueu5h"/><path class="pswfvabxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:booster-car-seat" {...props}></Icon>
