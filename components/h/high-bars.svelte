<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gve8z2b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gve8z2b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:high-bars" {...props}></Icon>
