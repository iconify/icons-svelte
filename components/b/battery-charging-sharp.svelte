<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7q87o6mu.css';
import '../../css/m/mnrm0dbsd.css';
import '../../css/d/dir4mc3_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u7q87o6mu"/><path class="mnrm0dbsd"/><path class="dir4mc3_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:battery-charging-sharp" {...props}></Icon>
