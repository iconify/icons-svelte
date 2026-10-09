<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpkg76b-y.css';
import '../../css/h/hbmkvs6fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tpkg76b-y"/><path class="hbmkvs6fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:insulation-roll-20" {...props}></Icon>
