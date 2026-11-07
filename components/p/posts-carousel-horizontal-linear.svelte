<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l5l1hedvi.css';
import '../../css/i/i96tnwb9m.css';
import '../../css/n/n9n4_cako.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l5l1hedvi"/><path class="i96tnwb9m"/><path class="n9n4_cako"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-horizontal-linear" {...props}></Icon>
