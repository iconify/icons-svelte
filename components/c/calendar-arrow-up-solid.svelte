<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c5f6bcbng.css';
import '../../css/v/vjegeb-cx.css';
import '../../css/x/xfcwl2bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c5f6bcbng"/><path class="vjegeb-cx"/><path class="xfcwl2bpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calendar-arrow-up-solid" {...props}></Icon>
