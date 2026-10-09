<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1mcems0k.css';
import '../../css/t/t_bk3zflf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="t_bk3zflf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:insulation-20-bold" {...props}></Icon>
