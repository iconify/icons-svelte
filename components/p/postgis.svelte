<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wugu-pb1m.css';
import '../../css/m/mn2rw-mej.css';
import '../../css/h/hp5s0iz9m.css';
import '../../css/k/k40q1abcl.css';
import '../../css/x/xomu_abkw.css';
import '../../css/z/zzb05gbtm.css';
import '../../css/i/ixkzc_bxb.css';
import '../../css/p/p6vvctrfm.css';
import '../../css/e/et8tnfdfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wugu-pb1m"/><path class="mn2rw-mej"/><path class="hp5s0iz9m"/><path class="k40q1abcl"/><path class="xomu_abkw"/><path class="zzb05gbtm"/><path class="ixkzc_bxb"/><path class="p6vvctrfm"/><path class="et8tnfdfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:postgis" {...props}></Icon>
