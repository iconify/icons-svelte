<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi9h__ikp.css';
import '../../css/h/hwt2tuv6e.css';
import '../../css/j/j_kppeg2r.css';
import '../../css/t/tfw8j54dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi9h__ikp"/><circle class="hwt2tuv6e"/><circle class="j_kppeg2r"/><circle class="tfw8j54dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:cheese" {...props}></Icon>
