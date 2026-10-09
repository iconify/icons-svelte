<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsp_74b5t.css';
import '../../css/p/p95ug3i0a.css';
import '../../css/h/h0fjfvbhi.css';
import '../../css/m/mpsu6eb-c.css';
import '../../css/d/dze8s_bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fsp_74b5t"/><path class="p95ug3i0a"/><path class="h0fjfvbhi"/><path class="mpsu6eb-c"/><path class="dze8s_bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:led-48-bold" {...props}></Icon>
