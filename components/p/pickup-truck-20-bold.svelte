<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7nzr5vfc.css';
import '../../css/w/wbrmur83b.css';
import '../../css/t/tlpzu3bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z7nzr5vfc"/><path class="wbrmur83b"/><path class="tlpzu3bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pickup-truck-20-bold" {...props}></Icon>
