<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk-jb4_bv.css';
import '../../css/y/yg49weaem.css';
import '../../css/k/kyq-juboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lk-jb4_bv"/><path clip-rule="evenodd" class="yg49weaem"/><path class="kyq-juboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:garage-solid" {...props}></Icon>
