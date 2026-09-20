<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wx2_qhbxs.css';
import '../../css/n/ny2yxtbss.css';
import '../../css/t/ta0zdfd_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wx2_qhbxs"/><path class="ny2yxtbss"/><path class="ta0zdfd_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:monitor-line-duotone" {...props}></Icon>
