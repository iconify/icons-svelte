<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nv1deiyek.css';
import '../../css/t/tioax3bil.css';
import '../../css/q/qjc0i83ur.css';
import '../../css/c/cjvudbbln.css';
import '../../css/t/thbuxufef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="nv1deiyek"/><path class="tioax3bil"/><path class="qjc0i83ur"/><path class="cjvudbbln"/><path class="thbuxufef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:reduce-two" {...props}></Icon>
