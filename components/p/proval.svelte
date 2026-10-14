<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qempt5bxh.css';
import '../../css/e/e7pfvbb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qempt5bxh"/><path class="e7pfvbb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proval" {...props}></Icon>
