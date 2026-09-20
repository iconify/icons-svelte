<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji63zhrdl.css';
import '../../css/c/cs7zjhbrw.css';
import '../../css/j/jomwdcxqo.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/o/o_d7gwb7s.css';
import '../../css/s/s51fiv1hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ji63zhrdl"/><path class="cs7zjhbrw"/><path class="jomwdcxqo"/><g class="jn8qy4bru"><path class="o_d7gwb7s"/><path class="s51fiv1hv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:computer-mouse" {...props}></Icon>
