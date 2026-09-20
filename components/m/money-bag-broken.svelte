<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/doete9yan.css';
import '../../css/w/wsvb1rbkf.css';
import '../../css/p/p11hmpggb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="doete9yan"/><path class="wsvb1rbkf"/><path class="p11hmpggb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:money-bag-broken" {...props}></Icon>
