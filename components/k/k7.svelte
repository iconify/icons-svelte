<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/une0tkb_h.css';
import '../../css/z/zxjr-cemx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="une0tkb_h"/><path class="zxjr-cemx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:k7" {...props}></Icon>
