<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj_qicchw.css';
import '../../css/m/mgkbe6uxk.css';
import '../../css/i/i7sr6ubzr.css';
import '../../css/g/g3gxxib9z.css';
import '../../css/s/sdj3236vq.css';
import '../../css/a/a8a4agb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj_qicchw"/><path class="mgkbe6uxk"/><path class="i7sr6ubzr"/><path class="g3gxxib9z"/><path class="sdj3236vq"/><path class="a8a4agb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-scheduler" {...props}></Icon>
