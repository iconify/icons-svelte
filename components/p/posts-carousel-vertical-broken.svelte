<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rct29b3qg.css';
import '../../css/e/ezkmwabnq.css';
import '../../css/j/janxgzbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rct29b3qg"/><path class="ezkmwabnq"/><path class="janxgzbgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-vertical-broken" {...props}></Icon>
