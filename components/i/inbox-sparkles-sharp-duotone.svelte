<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/b/bpck14box.css';
import '../../css/s/snibgdcaa.css';
import '../../css/i/i645x0uvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bpck14box"/><path class="snibgdcaa"/><path class="i645x0uvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:inbox-sparkles-sharp-duotone" {...props}></Icon>
