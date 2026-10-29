<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/h/hxpb80bjk.css';
import '../../css/x/xjj57vife.css';
import '../../css/f/fhns2vbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="hxpb80bjk"/><path class="xjj57vife"/><path class="fhns2vbpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:black-cat" {...props}></Icon>
