<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl9r37boe.css';
import '../../css/f/fmyd_bcdu.css';
import '../../css/g/gody8syjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vl9r37boe"/><path class="fmyd_bcdu"/><path class="gody8syjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:junit-wordmark" {...props}></Icon>
