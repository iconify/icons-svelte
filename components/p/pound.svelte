<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo-1d-f3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eo-1d-f3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pound" {...props}></Icon>
