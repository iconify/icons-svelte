<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/gpycsr50z.css';
import '../../css/t/th55hbb_y.css';
import '../../css/e/ehux52bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gpycsr50z"/><path class="th55hbb_y"/><path class="ehux52bxn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:google-sheet" {...props}></Icon>
