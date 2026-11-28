<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo5zm0b2e.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uxfqx7b8a.css';
import '../../css/l/lavl0lbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo5zm0b2e secondary"/><g class="dt0cm9dhy primary"><path class="uxfqx7b8a"/><path class="lavl0lbcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:octagon-dot-duo" {...props}></Icon>
