<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/llper-sbd.css';
import '../../css/s/s1756d84r.css';
import '../../css/e/efdecu-kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="llper-sbd"/><path class="s1756d84r"/><path class="efdecu-kr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:history-duotone" {...props}></Icon>
