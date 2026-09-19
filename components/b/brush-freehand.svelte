<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsbj687dq.css';
import '../../css/a/aib90vbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tsbj687dq"/><path class="aib90vbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:brush-freehand" {...props}></Icon>
