<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzn_9vblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dzn_9vblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:kidneys" {...props}></Icon>
