<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n5_fq3thg.css';
import '../../css/v/v7a2u9b3k.css';
import '../../css/e/e0cmz0boh.css';
import '../../css/t/t4qaumccy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n5_fq3thg"/><path class="v7a2u9b3k"/><path class="e0cmz0boh"/><path class="t4qaumccy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-text-broken" {...props}></Icon>
