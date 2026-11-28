<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwa3_zbyy.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i_dg2gbxb.css';
import '../../css/c/co23gdcen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwa3_zbyy secondary"/><g class="dt0cm9dhy primary"><path class="i_dg2gbxb"/><path class="co23gdcen"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:polaroid-duo" {...props}></Icon>
