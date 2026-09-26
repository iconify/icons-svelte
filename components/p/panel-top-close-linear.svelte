<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f-rbj8yzp.css';
import '../../css/s/s-28vgayl.css';
import '../../css/q/q2oyql66o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f-rbj8yzp"/><path class="s-28vgayl"/><path class="q2oyql66o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-close-linear" {...props}></Icon>
