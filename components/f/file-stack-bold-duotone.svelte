<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxmr-bbpl.css';
import '../../css/m/mjeg-y3pl.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/f/f09_mkvvu.css';
import '../../css/k/kv93igb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxmr-bbpl"/><path class="mjeg-y3pl"/><g class="xtpeb-edw"><path class="f09_mkvvu"/><path class="kv93igb5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-stack-bold-duotone" {...props}></Icon>
