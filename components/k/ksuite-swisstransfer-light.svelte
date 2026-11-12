<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iedyk4l4k.css';
import '../../css/x/xfes82bvz.css';
import '../../css/r/rzokr9xwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iedyk4l4k"/><path class="xfes82bvz"/><path class="rzokr9xwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-swisstransfer-light" {...props}></Icon>
