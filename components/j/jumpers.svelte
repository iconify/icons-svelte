<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fyxtxvbbl.css';
import '../../css/d/diom9iltf.css';
import '../../css/l/lkt0z6aco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fyxtxvbbl"/><path class="diom9iltf"/><path class="lkt0z6aco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:jumpers" {...props}></Icon>
