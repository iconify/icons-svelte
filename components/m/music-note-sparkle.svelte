<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fvkufybms.css';
import '../../css/s/sb191nbxw.css';
import '../../css/u/uu478ytul.css';
import '../../css/w/wcny-elpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fvkufybms"/><circle class="sb191nbxw"/><path class="uu478ytul"/><circle class="wcny-elpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-note-sparkle" {...props}></Icon>
