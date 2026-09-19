<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv67p9b9k.css';
import '../../css/u/unmzc2s1t.css';
import '../../css/a/a_oo1mbmr.css';
import '../../css/e/e7gwqvbfg.css';
import '../../css/s/sb-xycbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mv67p9b9k"/><path class="unmzc2s1t"/><path class="a_oo1mbmr"/><path class="e7gwqvbfg"/><path class="sb-xycbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dart" {...props}></Icon>
