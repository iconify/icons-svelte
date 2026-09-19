<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pihk1kufz.css';
import '../../css/n/n9_obdcgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="pihk1kufz"/><path class="n9_obdcgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:link" {...props}></Icon>
