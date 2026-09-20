<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rth2zpu4a.css';
import '../../css/k/kt1i1dx8i.css';
import '../../css/n/nyo6-kbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rth2zpu4a"/><path class="kt1i1dx8i"/><path class="nyo6-kbvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:layers-three-solid" {...props}></Icon>
