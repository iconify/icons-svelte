<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_mmmi5cu.css';
import '../../css/f/f-7xlbb5g.css';
import '../../css/q/qphgw4bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l_mmmi5cu"/><path class="f-7xlbb5g"/><path class="qphgw4bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earthing-switch-20" {...props}></Icon>
