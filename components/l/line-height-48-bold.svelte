<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdiyli40o.css';
import '../../css/p/pc-bfqbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hdiyli40o"/><path class="pc-bfqbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:line-height-48-bold" {...props}></Icon>
