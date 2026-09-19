<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s26cq-8xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="s26cq-8xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dumpster-fire" {...props}></Icon>
