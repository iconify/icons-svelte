<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a0njtnbcl.css';
import '../../css/j/j5gwsvbqu.css';
import '../../css/g/gq6m_vbam.css';
import '../../css/d/dxir9oplz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a0njtnbcl"/><path class="j5gwsvbqu"/><path class="gq6m_vbam"/><path class="dxir9oplz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:regex-duo" {...props}></Icon>
