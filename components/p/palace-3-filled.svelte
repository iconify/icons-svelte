<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx1ngfbkm.css';
import '../../css/n/n6y0s7eue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx1ngfbkm"/><path class="n6y0s7eue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:palace-3-filled" {...props}></Icon>
