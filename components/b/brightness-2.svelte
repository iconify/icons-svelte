<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6re6s5_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":432};
const content = `<path class="t6re6s5_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:brightness-2" {...props}></Icon>
