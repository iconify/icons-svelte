<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/eq3frqb0l.css';
import '../../css/p/pvxqdfbze.css';
import '../../css/t/thha3hpsz.css';
import '../../css/r/rdq30d3zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="eq3frqb0l"/><g class="pvxqdfbze"><path class="thha3hpsz"/><path class="rdq30d3zb"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-quote-line-duotone" {...props}></Icon>
