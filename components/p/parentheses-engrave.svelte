<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eh0001y2z.css';
import '../../css/g/gdii7cb0u.css';
import '../../css/v/v-6eycb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eh0001y2z"/><path class="gdii7cb0u wm-shadow"/><path class="v-6eycb-t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:parentheses-engrave" {...props}></Icon>
