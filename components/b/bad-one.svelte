<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhald_j0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mhald_j0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bad-one" {...props}></Icon>
