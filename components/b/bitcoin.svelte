<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9kihqb-w.css';
import '../../css/y/y37rc1b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z9kihqb-w"/><path class="y37rc1b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bitcoin" {...props}></Icon>
