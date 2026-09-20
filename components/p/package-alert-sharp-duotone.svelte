<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/c/c42n_vo5g.css';
import '../../css/y/yexjwyeak.css';
import '../../css/r/r4rw-imsf.css';
import '../../css/w/w8slmsefx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c42n_vo5g"/><path class="yexjwyeak"/><path class="r4rw-imsf"/><path class="w8slmsefx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-alert-sharp-duotone" {...props}></Icon>
