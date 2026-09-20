<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvwlbwmkn.css';
import '../../css/z/zw52su8no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vvwlbwmkn"/><path class="zw52su8no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lastpass" {...props}></Icon>
