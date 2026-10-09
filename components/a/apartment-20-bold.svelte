<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmuj25bzq.css';
import '../../css/l/llcw5u27i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pmuj25bzq"/><path class="llcw5u27i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apartment-20-bold" {...props}></Icon>
