<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2k1y2acb.css';
import '../../css/z/zhtix7bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2k1y2acb"/><path class="zhtix7bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart-check" {...props}></Icon>
