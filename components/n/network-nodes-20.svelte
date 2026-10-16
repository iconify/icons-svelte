<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7_bml7xz.css';
import '../../css/k/kte3hjbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s7_bml7xz"/><path class="kte3hjbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:network-nodes-20" {...props}></Icon>
