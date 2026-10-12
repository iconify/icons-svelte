<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6_8koigx.css';
import '../../css/u/u7v9-uihg.css';
import '../../css/y/y7fca_9em.css';
import '../../css/b/baxz_3tcy.css';
import '../../css/y/y23tjybgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x6_8koigx"/><path class="u7v9-uihg"/><path class="y7fca_9em"/><path class="baxz_3tcy"/><path class="y23tjybgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desk-globe-48" {...props}></Icon>
