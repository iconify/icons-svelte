<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/r/ryfxsnb7k.css';
import '../../css/t/t3g9whbyu.css';
import '../../css/f/fdp_8i46o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="ryfxsnb7k"/><path class="t3g9whbyu"/><path class="fdp_8i46o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:bell" {...props}></Icon>
