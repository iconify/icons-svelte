<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivsgoeb9g.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vw94lwbnx.css';
import '../../css/t/t5hr25ewh.css';
import '../../css/c/czibwhzzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivsgoeb9g secondary"/><g class="dt0cm9dhy primary"><path class="vw94lwbnx"/><path class="t5hr25ewh"/><path class="czibwhzzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-open-sparkles-duo" {...props}></Icon>
