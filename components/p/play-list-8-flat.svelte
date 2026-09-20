<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/spe2vy0_x.css';
import '../../css/i/ihob9llwi.css';
import '../../css/f/fe3otccrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="spe2vy0_x"/><path clip-rule="evenodd" class="ihob9llwi"/><path class="fe3otccrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:play-list-8-flat" {...props}></Icon>
