<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka0hemtmx.css';
import '../../css/c/cm0047wom.css';
import '../../css/i/ij08oib1e.css';
import '../../css/o/opl2tbcms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ka0hemtmx"/><path class="cm0047wom"/><path class="ij08oib1e"/><path class="opl2tbcms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:qr-code-20" {...props}></Icon>
