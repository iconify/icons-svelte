<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdxbmxx-r.css';
import '../../css/k/kh7uvqjfd.css';
import '../../css/u/uqem58bur.css';
import '../../css/s/sx9388beu.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 tdxbmxx-r"/><path class="clr-i-outline clr-i-outline-path-2 kh7uvqjfd"/><path class="clr-i-outline clr-i-outline-path-3 uqem58bur"/><path class="clr-i-outline clr-i-outline-path-4 sx9388beu"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:bar-chart-line" {...props}></Icon>
