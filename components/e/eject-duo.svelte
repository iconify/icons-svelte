<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hemiprbfx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xei5bkbrz.css';
import '../../css/s/sxa77d4ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hemiprbfx secondary"/><g class="dt0cm9dhy primary"><path class="xei5bkbrz"/><path class="sxa77d4ni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:eject-duo" {...props}></Icon>
