<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxcq0gbtc.css';
import '../../css/n/n79s7ib_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxcq0gbtc"/><path clip-rule="evenodd" class="n79s7ib_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:letter-opened-bold" {...props}></Icon>
