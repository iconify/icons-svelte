<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agj07mbsi.css';
import '../../css/d/dmuhyjbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="agj07mbsi"/><path class="dmuhyjbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phase-shifter-48-bold" {...props}></Icon>
