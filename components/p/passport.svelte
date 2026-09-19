<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tcke7pbqg.css';
import '../../css/y/y-qjg-szy.css';
import '../../css/c/cnngty1vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tcke7pbqg"/><path class="y-qjg-szy"/><path class="cnngty1vp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:passport" {...props}></Icon>
