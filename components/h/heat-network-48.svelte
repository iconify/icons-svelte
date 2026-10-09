<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa-dagiaz.css';
import '../../css/k/kialax5-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oa-dagiaz"/><path class="kialax5-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-network-48" {...props}></Icon>
