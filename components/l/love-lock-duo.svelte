<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/w8rvwhbnt.css';
import '../../css/h/hl1kwacuc.css';
import '../../css/h/h7a9wibzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="w8rvwhbnt"/><path class="hl1kwacuc wm-a"/><path class="h7a9wibzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:love-lock-duo" {...props}></Icon>
