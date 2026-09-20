<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wvcj-vi3u.css';
import '../../css/a/a0ljpns4v.css';
import '../../css/k/kyzqyvbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wvcj-vi3u"/><path class="a0ljpns4v"/><path class="kyzqyvbjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flip-vertical-broken" {...props}></Icon>
