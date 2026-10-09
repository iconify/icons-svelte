<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u19njwbvz.css';
import '../../css/s/s7vp-wbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u19njwbvz"/><path class="s7vp-wbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-left-48-bold" {...props}></Icon>
