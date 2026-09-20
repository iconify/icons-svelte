<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kacyy2b3k.css';
import '../../css/r/rpvb-o6bq.css';
import '../../css/c/cn7qxlbmw.css';
import '../../css/y/y0ugp8bhh.css';
import '../../css/k/ka6_r4z_y.css';
import '../../css/i/ilh0h1bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle transform="rotate(-45)" class="kacyy2b3k"/><g class="rpvb-o6bq"><circle transform="rotate(-45)" class="cn7qxlbmw"/><path class="y0ugp8bhh"/><path class="ka6_r4z_y"/></g><path class="ilh0h1bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:lollipop" {...props}></Icon>
