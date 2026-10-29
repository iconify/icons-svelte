<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/ca-1d_bkz.css';
import '../../css/y/yr1wpj77v.css';
import '../../css/p/p_kl59b1m.css';
import '../../css/j/j90xqmbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ca-1d_bkz"/><path class="wm-shadow yr1wpj77v"/><path class="p_kl59b1m"/><path class="j90xqmbyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hourglass-engrave" {...props}></Icon>
