<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr34_cbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="wr34_cbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:money-bill-1" {...props}></Icon>
