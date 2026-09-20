<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cua72wbew.css';
import '../../css/x/xltwp_47m.css';
import '../../css/k/klo26abzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cua72wbew"/><path class="xltwp_47m"/><path class="klo26abzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qdrant-dark" {...props}></Icon>
