<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilfwspl_f.css';
import '../../css/c/cvojyd_oj.css';
import '../../css/j/jlkzze14k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ilfwspl_f"/><path class="cvojyd_oj"/><path class="jlkzze14k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glances" {...props}></Icon>
