<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d58q_4bdh.css';
import '../../css/f/fg-hc3ysv.css';
import '../../css/j/japrfgbml.css';
import '../../css/c/c3xus2otf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d58q_4bdh"/><path class="fg-hc3ysv"/><path class="japrfgbml"/><path class="c3xus2otf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-read-broken" {...props}></Icon>
