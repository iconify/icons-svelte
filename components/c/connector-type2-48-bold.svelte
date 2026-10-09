<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra-t_bbyc.css';
import '../../css/c/c7l7flb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ra-t_bbyc"/><path class="c7l7flb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-type2-48-bold" {...props}></Icon>
