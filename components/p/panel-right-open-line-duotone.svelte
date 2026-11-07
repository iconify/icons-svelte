<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lt87iveio.css';
import '../../css/i/ip-kvve8g.css';
import '../../css/y/yma2139fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lt87iveio"/><path class="ip-kvve8g"/><path class="yma2139fj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-right-open-line-duotone" {...props}></Icon>
