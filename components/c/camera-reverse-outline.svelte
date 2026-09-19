<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2vpa7-wx.css';
import '../../css/a/aytccm9qb.css';
import '../../css/l/lqxjulbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h2vpa7-wx"/><path class="aytccm9qb"/><path class="lqxjulbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:camera-reverse-outline" {...props}></Icon>
