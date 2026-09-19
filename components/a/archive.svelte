<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/l/l_jvi_-3i.css';
import '../../css/y/yclr26l0t.css';
import '../../css/t/tovsduesy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="l_jvi_-3i"/><path class="yclr26l0t"/><path class="tovsduesy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:archive" {...props}></Icon>
