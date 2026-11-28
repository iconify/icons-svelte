<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slknnlbbl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uxfqx7b8a.css';
import '../../css/w/wkbb-c3nd.css';
import '../../css/l/ln33cc_mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary slknnlbbl"/><g class="dt0cm9dhy primary"><path class="uxfqx7b8a"/><path class="wkbb-c3nd"/><path class="ln33cc_mx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:octagon-alert-duo" {...props}></Icon>
