<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wht_zowdm.css';
import '../../css/f/fmvl9jb-y.css';
import '../../css/i/iw07ocizs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wht_zowdm"/><path class="fmvl9jb-y wm-a"/><path class="iw07ocizs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:refrigerator-duo" {...props}></Icon>
