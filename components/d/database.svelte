<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/y95393_dl.css';
import '../../css/i/i-7a-zb9i.css';
import '../../css/o/o53n0ib2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="y95393_dl"/><path class="i-7a-zb9i"/><path class="o53n0ib2h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:database" {...props}></Icon>
