<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocavnt7jz.css';
import '../../css/k/kkhl62fff.css';
import '../../css/w/wt1f10gjm.css';
import '../../css/g/gvlyjsbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocavnt7jz"/><path class="kkhl62fff"/><path class="wt1f10gjm"/><path clip-rule="evenodd" class="gvlyjsbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-dots-outline" {...props}></Icon>
