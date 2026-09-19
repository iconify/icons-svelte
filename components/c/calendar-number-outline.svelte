<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvtzd3b0t.css';
import '../../css/l/llds493te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="zvtzd3b0t"/><path class="llds493te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:calendar-number-outline" {...props}></Icon>
