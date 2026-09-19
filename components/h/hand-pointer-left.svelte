<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqtcx1wqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":448};
const content = `<path class="vqtcx1wqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:hand-pointer-left" {...props}></Icon>
