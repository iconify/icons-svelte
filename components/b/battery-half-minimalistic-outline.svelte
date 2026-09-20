<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vun0ddrph.css';
import '../../css/s/sv57hgpcx.css';
import '../../css/i/iin1g9v9i.css';
import '../../css/x/x1rqnf35i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vun0ddrph"/><path class="sv57hgpcx"/><path clip-rule="evenodd" class="iin1g9v9i"/><path class="x1rqnf35i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-half-minimalistic-outline" {...props}></Icon>
