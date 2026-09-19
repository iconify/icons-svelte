<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/l/l0kcx-bur.css';
import '../../css/d/d0lh95rjb.css';
import '../../css/x/xl67sbtid.css';
import '../../css/f/focknpd0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="d2kvgvbvc"><path class="l0kcx-bur"/><path class="d0lh95rjb"/><path class="xl67sbtid"/><path class="focknpd0m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:opengl" {...props}></Icon>
