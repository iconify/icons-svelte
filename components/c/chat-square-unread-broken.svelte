<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tzeltiq8g.css';
import '../../css/a/a5kojgb5c.css';
import '../../css/u/u00ey8bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tzeltiq8g"/><path class="a5kojgb5c"/><circle class="u00ey8bps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-unread-broken" {...props}></Icon>
