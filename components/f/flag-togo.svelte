<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcpth-wqs.css';
import '../../css/u/upxyo7b5y.css';
import '../../css/q/qg4z8dbtu.css';
import '../../css/s/s-ks1rd8k.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wcpth-wqs"/><path class="upxyo7b5y"/><path class="qg4z8dbtu"/><path class="s-ks1rd8k"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-togo" {...props}></Icon>
