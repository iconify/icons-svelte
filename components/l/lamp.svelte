<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-3m0x4_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l-3m0x4_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:lamp" {...props}></Icon>
