<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t90i62flf.css';
import '../../css/r/re_renben.css';
import '../../css/a/aw5f0f-8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t90i62flf"/><path class="re_renben"/><path class="aw5f0f-8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paypal" {...props}></Icon>
