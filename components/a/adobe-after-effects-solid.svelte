<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv4m5hauv.css';
import '../../css/t/tma0dchkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv4m5hauv"/><path clip-rule="evenodd" class="tma0dchkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:adobe-after-effects-solid" {...props}></Icon>
