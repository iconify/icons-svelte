<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri3k7ob7e.css';
import '../../css/a/a-4s07bqr.css';
import '../../css/t/t8dqc66mp.css';
import '../../css/p/pwmnyqitk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ri3k7ob7e"/><path class="a-4s07bqr"/><path class="t8dqc66mp"/><path class="pwmnyqitk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-x-48" {...props}></Icon>
