<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuy3_33xc.css';
import '../../css/p/p3uaq9bss.css';
import '../../css/a/a4ahv-08i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="wuy3_33xc"/><path class="p3uaq9bss"/><path class="a4ahv-08i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:mq-4x3" {...props}></Icon>
