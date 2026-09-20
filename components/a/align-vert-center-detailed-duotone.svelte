<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oid7mlb3a.css';
import '../../css/v/vxqb2ubqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oid7mlb3a"/><path class="vxqb2ubqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-vert-center-detailed-duotone" {...props}></Icon>
