<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k4-c7ob6h.css';
import '../../css/w/w7_mhrwuu.css';
import '../../css/i/ijb5i-b9c.css';
import '../../css/h/h_-fe7h9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k4-c7ob6h"/><path class="w7_mhrwuu"/><path class="ijb5i-b9c"/><path class="h_-fe7h9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calendar-search" {...props}></Icon>
