<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u2fm9-b4c.css';
import '../../css/r/rnav8kb8d.css';
import '../../css/h/h8fjzdb4w.css';
import '../../css/p/pwxlsdbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u2fm9-b4c"/><path clip-rule="evenodd" class="rnav8kb8d"/><path clip-rule="evenodd" class="h8fjzdb4w"/><path class="pwxlsdbcv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-call-bold-duotone" {...props}></Icon>
