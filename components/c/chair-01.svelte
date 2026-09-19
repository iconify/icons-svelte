<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o3bsa3b3l.css';
import '../../css/o/ognykqjii.css';
import '../../css/x/xzgh_vbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o3bsa3b3l"/><path class="ognykqjii"/><path class="xzgh_vbuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chair-01" {...props}></Icon>
