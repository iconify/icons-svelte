<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hnut4_biv.css';
import '../../css/s/s-k1_mf2k.css';
import '../../css/a/axni4fzcl.css';
import '../../css/i/isx3pjbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="hnut4_biv"/><path class="s-k1_mf2k"/><rect class="axni4fzcl"/><rect class="isx3pjbzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:game-console-one" {...props}></Icon>
