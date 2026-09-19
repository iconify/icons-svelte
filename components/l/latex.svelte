<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l911c10ro.css';
import '../../css/o/owjtq1bck.css';
import '../../css/b/bscpnfz0g.css';
import '../../css/n/nr8-grdud.css';
import '../../css/b/bzia22n1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l911c10ro"/><path class="owjtq1bck"/><path class="bscpnfz0g"/><path class="nr8-grdud"/><path class="bzia22n1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:latex" {...props}></Icon>
