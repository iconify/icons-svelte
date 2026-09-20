<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv91rzblu.css';
import '../../css/q/qsg0-jb6l.css';
import '../../css/r/rndt1hbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bv91rzblu"/><path class="qsg0-jb6l"/><path class="rndt1hbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:fingerprint" {...props}></Icon>
