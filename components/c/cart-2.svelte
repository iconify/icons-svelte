<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4cc3ab5d.css';
import '../../css/y/ysifiqi0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t4cc3ab5d"/><path class="ysifiqi0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cart-2" {...props}></Icon>
