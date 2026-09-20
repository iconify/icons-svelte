<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/a/a7kmjvbvt.css';
import '../../css/l/l0yw3t1ep.css';
import '../../css/e/eehirac9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="a7kmjvbvt"/><path class="l0yw3t1ep"/><path class="eehirac9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:episodes" {...props}></Icon>
