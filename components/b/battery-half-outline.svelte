<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/swy3tebjf.css';
import '../../css/e/e5m4qbbih.css';
import '../../css/b/bku0ur4-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="swy3tebjf"/><path class="e5m4qbbih"/><path clip-rule="evenodd" class="bku0ur4-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-half-outline" {...props}></Icon>
