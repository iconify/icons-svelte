<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q79rvz6zn.css';
import '../../css/r/rv25bpjtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="q79rvz6zn"/><path class="rv25bpjtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:2hearts" {...props}></Icon>
