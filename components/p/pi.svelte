<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/x/xipf1qcsp.css';
import '../../css/r/r4gai5bjn.css';
import '../../css/l/lf-g9db-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="xipf1qcsp"/><path class="r4gai5bjn"/><path class="lf-g9db-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:pi" {...props}></Icon>
