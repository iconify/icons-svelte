<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/exetrlbof.css';
import '../../css/g/g8dwmbbzj.css';
import '../../css/u/uzjqjlk8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="exetrlbof"/><path class="g8dwmbbzj"/><path class="uzjqjlk8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:feed-broken" {...props}></Icon>
