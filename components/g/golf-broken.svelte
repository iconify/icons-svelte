<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/owzpq1dsn.css';
import '../../css/y/ya4v2ogmm.css';
import '../../css/h/hzret1bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="owzpq1dsn"/><path class="ya4v2ogmm"/><path class="hzret1bgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:golf-broken" {...props}></Icon>
