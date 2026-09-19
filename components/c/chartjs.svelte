<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftpedcbgb.css';
import '../../css/a/ai4ebubxr.css';
import '../../css/i/i3dab3_cs.css';
import '../../css/w/wfceq4bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ftpedcbgb"/><path class="ai4ebubxr"/><path class="i3dab3_cs"/><path class="wfceq4bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:chartjs" {...props}></Icon>
