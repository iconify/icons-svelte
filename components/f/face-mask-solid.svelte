<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wg3_g8b9x.css';
import '../../css/l/lpiqk9bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="wg3_g8b9x"/><path class="lpiqk9bvy wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:face-mask-solid" {...props}></Icon>
