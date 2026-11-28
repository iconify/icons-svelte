<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/psqiixwqa.css';
import '../../css/i/i5s4dnbbr.css';
import '../../css/s/snn11qb0s.css';
import '../../css/t/twdzmxv9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="psqiixwqa"/><path class="i5s4dnbbr"/><path class="snn11qb0s"/><path class="twdzmxv9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:beer" {...props}></Icon>
