<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k2j4asbpi.css';
import '../../css/c/chja7twbz.css';
import '../../css/w/wglt83b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k2j4asbpi"/><path class="chja7twbz"/><path class="wglt83b5r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:layers-broken" {...props}></Icon>
