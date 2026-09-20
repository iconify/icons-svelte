<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zidfd5b0r.css';
import '../../css/w/wb4b4ktjg.css';
import '../../css/t/tgdoe1bss.css';
import '../../css/c/cbokru48w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zidfd5b0r"/><path class="wb4b4ktjg"/><path class="tgdoe1bss"/><path class="cbokru48w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:archivebox" {...props}></Icon>
