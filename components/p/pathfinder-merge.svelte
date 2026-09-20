<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y113zabih.css';
import '../../css/n/ndrw9nivs.css';
import '../../css/m/mi48ctyhi.css';
import '../../css/w/wl1pkfb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="y113zabih"/><path class="ndrw9nivs"/><path class="mi48ctyhi"/><path class="wl1pkfb3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:pathfinder-merge" {...props}></Icon>
