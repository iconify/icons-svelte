<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmnb66mry.css';
import '../../css/z/z46nhhf2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lmnb66mry"/><path class="z46nhhf2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bolt-diy" {...props}></Icon>
