<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o20t1r6ee.css';
import '../../css/o/o121o_9mq.css';
import '../../css/b/bghfy0b3k.css';
import '../../css/c/c3siailnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="o20t1r6ee"/><path class="o121o_9mq"/><path class="bghfy0b3k"/><path class="c3siailnp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-filter-x" {...props}></Icon>
