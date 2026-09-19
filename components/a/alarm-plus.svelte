<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1q-f9vcx.css';
import '../../css/u/uyp_7-bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1q-f9vcx"/><path class="uyp_7-bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-plus" {...props}></Icon>
