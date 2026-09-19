<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5tpnz--a.css';
import '../../css/q/qn50x0b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5tpnz--a"/><path class="qn50x0b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:mobile" {...props}></Icon>
