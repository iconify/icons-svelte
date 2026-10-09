<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfmop767n.css';
import '../../css/r/r5try_ncs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gfmop767n"/><path class="r5try_ncs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bridge-48-bold" {...props}></Icon>
