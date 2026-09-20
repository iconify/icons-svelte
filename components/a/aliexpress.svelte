<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuc4qxb-w.css';
import '../../css/n/n3l1s8lfb.css';
import '../../css/g/gy3y47_du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yuc4qxb-w"/><path class="n3l1s8lfb"/><path class="gy3y47_du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aliexpress" {...props}></Icon>
