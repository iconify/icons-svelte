<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjes_2big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cjes_2big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:metro-48" {...props}></Icon>
