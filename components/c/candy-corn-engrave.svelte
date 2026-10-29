<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jaline93j.css';
import '../../css/n/nyqj-4wfl.css';
import '../../css/d/dxfilmbdx.css';
import '../../css/a/a4vjoxyvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jaline93j wm-k"/><path class="nyqj-4wfl wm-shadow"/><path class="dxfilmbdx wm-k"/><path class="a4vjoxyvs wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:candy-corn-engrave" {...props}></Icon>
