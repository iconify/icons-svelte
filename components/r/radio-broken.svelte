<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c6lafhbvk.css';
import '../../css/w/w6ca74b2j.css';
import '../../css/s/smls78shz.css';
import '../../css/n/nau4w8dar.css';
import '../../css/n/n787bfb7v.css';
import '../../css/p/py99o21wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c6lafhbvk"/><path class="w6ca74b2j"/><path class="smls78shz"/><path class="nau4w8dar"/><path class="n787bfb7v"/><path class="py99o21wd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radio-broken" {...props}></Icon>
