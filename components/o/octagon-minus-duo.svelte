<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slknnlbbl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uxfqx7b8a.css';
import '../../css/k/kbe5qkb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary slknnlbbl"/><g class="dt0cm9dhy primary"><path class="uxfqx7b8a"/><path class="kbe5qkb7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:octagon-minus-duo" {...props}></Icon>
