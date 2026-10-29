<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zdv2jph6r.css';
import '../../css/u/u1of9ltii.css';
import '../../css/l/lg-8n1num.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zdv2jph6r"/><path class="u1of9ltii wm-a"/><path class="lg-8n1num"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:grid-2x2-duo" {...props}></Icon>
