<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myl6d8w3w.css';
import '../../css/b/b4otazbmd.css';
import '../../css/k/krk28sopl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="myl6d8w3w"/><path class="b4otazbmd"/><path class="krk28sopl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flow-meter-20" {...props}></Icon>
