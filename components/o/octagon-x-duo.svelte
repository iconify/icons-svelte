<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slknnlbbl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uxfqx7b8a.css';
import '../../css/l/lsums62it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary slknnlbbl"/><g class="dt0cm9dhy primary"><path class="uxfqx7b8a"/><path class="lsums62it"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:octagon-x-duo" {...props}></Icon>
