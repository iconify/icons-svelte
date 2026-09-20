<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe8ilbs_y.css';
import '../../css/i/i-jzrbbnk.css';
import '../../css/r/r0ixaf-0p.css';
import '../../css/c/conjjsbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":367.5,"height":45};
const content = `<path class="pe8ilbs_y"/><path class="i-jzrbbnk"/><path class="r0ixaf-0p"/><path class="conjjsbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:productboard-dark" {...props}></Icon>
