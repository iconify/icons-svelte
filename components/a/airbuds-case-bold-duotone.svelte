<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cng445bcg.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/v/v046j2erx.css';
import '../../css/h/hzza3-bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cng445bcg"/><g class="xtpeb-edw"><path class="v046j2erx"/><path class="hzza3-bxa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-case-bold-duotone" {...props}></Icon>
