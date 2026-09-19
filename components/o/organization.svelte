<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt59w0z1x.css';
import '../../css/u/upwskszgb.css';
import '../../css/p/pqv887qbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jt59w0z1x"/><path class="upwskszgb"/><path class="pqv887qbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:organization" {...props}></Icon>
