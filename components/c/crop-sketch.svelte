<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gmt1fkdfv.css';
import '../../css/f/fm6rs2b9w.css';
import '../../css/n/npx1ntq6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gmt1fkdfv"/><path class="fm6rs2b9w"/><path class="npx1ntq6p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:crop-sketch" {...props}></Icon>
