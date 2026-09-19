<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/f/fg7b3kb3a.css';
import '../../css/t/t0m0k5svp.css';
import '../../css/g/gu96anbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="fg7b3kb3a"/><path class="t0m0k5svp"/><path class="gu96anbik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:music-note" {...props}></Icon>
