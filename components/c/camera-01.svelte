<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zk6m5lngz.css';
import '../../css/n/ncss8tx5f.css';
import '../../css/c/cb8u71hty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zk6m5lngz"/><path class="ncss8tx5f"/><path class="cb8u71hty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:camera-01" {...props}></Icon>
