<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/ny68qsbjy.css';
import '../../css/g/gjo1tztxm.css';
import '../../css/u/uqhik9b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ny68qsbjy"/><path class="gjo1tztxm"/><path class="uqhik9b3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:history-3-line-duotone" {...props}></Icon>
