<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/isb-x7b4z.css';
import '../../css/s/s1afeeb0i.css';
import '../../css/t/t24d_rbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="isb-x7b4z"/><path class="s1afeeb0i wm-a"/><path class="t24d_rbut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:code" {...props}></Icon>
