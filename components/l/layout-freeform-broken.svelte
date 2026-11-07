<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aqn8_gw_r.css';
import '../../css/f/fqu4-ynwx.css';
import '../../css/h/h3hjjdb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aqn8_gw_r"/><path class="fqu4-ynwx"/><path class="h3hjjdb4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:layout-freeform-broken" {...props}></Icon>
