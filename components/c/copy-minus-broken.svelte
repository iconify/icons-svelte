<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t60_6fbkn.css';
import '../../css/n/n6gwi0b2o.css';
import '../../css/g/g2e37sboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t60_6fbkn"/><path class="n6gwi0b2o"/><path class="g2e37sboy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-minus-broken" {...props}></Icon>
