<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpjk8pbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpjk8pbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dashboard-gear" {...props}></Icon>
