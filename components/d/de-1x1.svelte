<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc9p2pbgb.css';
import '../../css/f/fox9vr5aw.css';
import '../../css/a/a6e_se6xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sc9p2pbgb"/><path class="fox9vr5aw"/><path class="a6e_se6xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:de-1x1" {...props}></Icon>
