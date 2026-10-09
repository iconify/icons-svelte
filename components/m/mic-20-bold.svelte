<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uih-zwlau.css';
import '../../css/p/pc3rltyei.css';
import '../../css/r/rltagccoa.css';
import '../../css/a/an84ox-sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uih-zwlau"/><path class="pc3rltyei"/><path class="rltagccoa"/><path class="an84ox-sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mic-20-bold" {...props}></Icon>
