<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evibsbc4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="evibsbc4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:replenishment-outline" {...props}></Icon>
