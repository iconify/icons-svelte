<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ij5db5ezo.css';
import '../../css/u/un4i8zbgk.css';
import '../../css/p/pgyhgdc3l.css';
import '../../css/v/vi8f91b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ij5db5ezo"/><path class="un4i8zbgk"/><path class="pgyhgdc3l"/><path class="vi8f91b0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chart2-duotone" {...props}></Icon>
