<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjio485oq.css';
import '../../css/b/bfmu8u6wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjio485oq"/><path class="bfmu8u6wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nakama-dark" {...props}></Icon>
