<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj084fw9a.css';
import '../../css/x/xzn_it8jp.css';
import '../../css/b/by0-yumdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj084fw9a"/><path class="xzn_it8jp"/><path class="by0-yumdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-4-bold-duotone" {...props}></Icon>
