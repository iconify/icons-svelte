<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/v/v5zhtkbbw.css';
import '../../css/e/eh4vwp2pz.css';
import '../../css/b/baq_7_bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="v5zhtkbbw wm-shadow"/><path class="eh4vwp2pz wm-shadow"/><path class="baq_7_bee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:person-running" {...props}></Icon>
