<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smjtv-oxv.css';
import '../../css/y/yixl0qbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="smjtv-oxv"/><path class="yixl0qbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:presentation-48" {...props}></Icon>
