<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_pzyr42v.css';
import '../../css/f/f5mkxw1-g.css';
import '../../css/q/qqj91ccql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_pzyr42v"/><path class="f5mkxw1-g"/><path class="qqj91ccql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:documents" {...props}></Icon>
