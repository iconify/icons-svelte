<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/stzn1tb6p.css';
import '../../css/u/u0jy2c12v.css';
import '../../css/n/n8guz-bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="stzn1tb6p"/><circle class="u0jy2c12v"/><path class="n8guz-bso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:msg-bubble-user-filled" {...props}></Icon>
