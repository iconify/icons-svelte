<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dz9ro_bbx.css';
import '../../css/j/jsjamhb6g.css';
import '../../css/r/rxdutob5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dz9ro_bbx"/><path class="jsjamhb6g"/><path class="rxdutob5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-preview-01" {...props}></Icon>
