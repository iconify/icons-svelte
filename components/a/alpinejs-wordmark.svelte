<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tblo-pfoi.css';
import '../../css/s/s26yw0bri.css';
import '../../css/m/mdbg4dcqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tblo-pfoi"/><path clip-rule="evenodd" class="s26yw0bri"/><path clip-rule="evenodd" class="mdbg4dcqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:alpinejs-wordmark" {...props}></Icon>
