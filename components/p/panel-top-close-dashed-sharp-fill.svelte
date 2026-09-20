<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/n/nz4nte95p.css';
import '../../css/j/jgv618mbj.css';
import '../../css/z/zvepp4dfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nz4nte95p"/><path class="jgv618mbj"/><path class="zvepp4dfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-top-close-dashed-sharp-fill" {...props}></Icon>
