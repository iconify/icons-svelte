<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc93vrbkc.css';
import '../../css/z/zho_0_ruy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc93vrbkc"/><path class="zho_0_ruy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rewind-filled" {...props}></Icon>
