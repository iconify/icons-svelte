<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/yzqd_nbaw.css';
import '../../css/p/pp3v195nj.css';
import '../../css/r/rs-d_y_0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yzqd_nbaw"/><circle class="pp3v195nj"/><circle class="rs-d_y_0o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-8-square" {...props}></Icon>
