<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x4rmvcc_s.css';
import '../../css/s/swm90vkhe.css';
import '../../css/i/isdk7pbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="x4rmvcc_s"/><path class="swm90vkhe"/><path class="isdk7pbrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cart-large-duotone" {...props}></Icon>
