<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v6yy0cbrr.css';
import '../../css/a/alio6gcxk.css';
import '../../css/l/lfeqacy5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="v6yy0cbrr"/><path class="alio6gcxk wm-a"/><path class="lfeqacy5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-monster-fluffy" {...props}></Icon>
