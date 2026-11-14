<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e6tif6bqs.css';
import '../../css/r/rj_bktros.css';
import '../../css/d/ddf0atlim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e6tif6bqs"/><path class="rj_bktros"/><path class="ddf0atlim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-minus-02" {...props}></Icon>
