<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dh-362btw.css';
import '../../css/c/c2ccr1cfe.css';
import '../../css/h/hvt2a6e9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dh-362btw"/><path class="c2ccr1cfe"/><path class="hvt2a6e9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:armchair-linear" {...props}></Icon>
