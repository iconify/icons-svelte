<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt65pdnfo.css';
import '../../css/z/zj1ulpbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="yt65pdnfo"/><path class="zj1ulpbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:body-outline" {...props}></Icon>
