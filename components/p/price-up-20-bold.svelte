<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt6n36bom.css';
import '../../css/i/i5jbbacbv.css';
import '../../css/e/egl9w0p1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gt6n36bom"/><path class="i5jbbacbv"/><path class="egl9w0p1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-up-20-bold" {...props}></Icon>
