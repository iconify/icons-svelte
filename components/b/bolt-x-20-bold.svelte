<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilu3h65we.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/v/vox66xuav.css';
import '../../css/g/gdinynbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ilu3h65we"/><path class="aqsnv9bnd"/><path class="vox66xuav"/><path class="gdinynbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-x-20-bold" {...props}></Icon>
