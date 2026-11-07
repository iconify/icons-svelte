<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/odm4k55bk.css';
import '../../css/f/f7azv0kip.css';
import '../../css/g/gyeonr9rw.css';
import '../../css/i/isdvmhtpq.css';
import '../../css/b/bktvtjwub.css';
import '../../css/v/vt32oynxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="odm4k55bk"/><path class="f7azv0kip"/><path class="gyeonr9rw"/><path class="isdvmhtpq"/><path class="bktvtjwub"/><path class="vt32oynxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:point-on-map-perspective-broken" {...props}></Icon>
