<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/k/kdnqezbvd.css';
import '../../css/i/iufaf7g1w.css';
import '../../css/a/a9jjuv2wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="d2kvgvbvc"><path class="kdnqezbvd"/><path class="iufaf7g1w"/><path class="a9jjuv2wa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:bw-1x1" {...props}></Icon>
