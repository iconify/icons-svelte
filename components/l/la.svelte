<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rd8b6f9us.css';
import '../../css/g/gi_d5y8ek.css';
import '../../css/j/j0rvlxkbk.css';
import '../../css/h/hibut_iow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rd8b6f9us"/><path class="gi_d5y8ek"/><path class="j0rvlxkbk"/><path class="hibut_iow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:la" {...props}></Icon>
