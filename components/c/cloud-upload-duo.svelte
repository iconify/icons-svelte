<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h9rr08b1k.css';
import '../../css/g/gpzldrb9z.css';
import '../../css/m/m2ebxhp-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="h9rr08b1k"/><path class="gpzldrb9z wm-s"/><path class="m2ebxhp-u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-upload-duo" {...props}></Icon>
