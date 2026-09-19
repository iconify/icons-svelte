<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h1m10_v9q.css';
import '../../css/h/hl3-0tb6x.css';
import '../../css/j/j55g2km1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="h1m10_v9q"/><path class="hl3-0tb6x"/><path class="j55g2km1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:flying-human" {...props}></Icon>
