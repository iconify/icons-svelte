<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6e8x3psq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6e8x3psq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-transfer-diagonal-outline" {...props}></Icon>
