<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of8ozpb-y.css';
import '../../css/n/nk1dwkb8d.css';
import '../../css/t/tm6yvh82x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="of8ozpb-y"/><path class="nk1dwkb8d"/><path class="tm6yvh82x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:helideck-48-bold" {...props}></Icon>
