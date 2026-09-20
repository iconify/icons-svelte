<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wn8ltlbkj.css';
import '../../css/x/x1va69ceo.css';
import '../../css/f/fe0lorb6j.css';
import '../../css/g/gewiseacf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wn8ltlbkj"/><path clip-rule="evenodd" class="x1va69ceo"/><path clip-rule="evenodd" class="fe0lorb6j"/><path clip-rule="evenodd" class="gewiseacf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-large-outline" {...props}></Icon>
