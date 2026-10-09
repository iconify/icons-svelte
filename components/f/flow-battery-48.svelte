<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvvf71v4s.css';
import '../../css/k/krurd6_gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nvvf71v4s"/><path class="krurd6_gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flow-battery-48" {...props}></Icon>
