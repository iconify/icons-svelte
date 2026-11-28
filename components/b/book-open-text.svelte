<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/th4j2yb1q.css';
import '../../css/c/cyk-_qf_o.css';
import '../../css/s/sk-gc6smq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="th4j2yb1q"/><path class="cyk-_qf_o"/><path class="sk-gc6smq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-open-text" {...props}></Icon>
