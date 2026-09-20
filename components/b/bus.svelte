<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i0382plgr.css';
import '../../css/f/f59u7ybax.css';
import '../../css/p/pb7-4j_bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i0382plgr"/><path clip-rule="evenodd" class="f59u7ybax"/><path class="pb7-4j_bc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:bus" {...props}></Icon>
