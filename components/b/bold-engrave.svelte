<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nbbbucc-k.css';
import '../../css/j/jpijyacjj.css';
import '../../css/r/r1-lpnfzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nbbbucc-k"/><path class="jpijyacjj wm-shadow"/><path class="r1-lpnfzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bold-engrave" {...props}></Icon>
