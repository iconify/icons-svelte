<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vniy-9pnf.css';
import '../../css/r/rp8lt1bxe.css';
import '../../css/j/jmlntsbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vniy-9pnf"/><path class="rp8lt1bxe"/><path class="jmlntsbsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:news-duotone" {...props}></Icon>
