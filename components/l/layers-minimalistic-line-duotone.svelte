<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bb8l5mttt.css';
import '../../css/o/ohnkn1dtv.css';
import '../../css/s/s-vjqccqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bb8l5mttt"/><path class="ohnkn1dtv"/><path class="s-vjqccqw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:layers-minimalistic-line-duotone" {...props}></Icon>
