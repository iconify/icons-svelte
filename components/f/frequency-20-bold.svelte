<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixcl-v7ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ixcl-v7ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frequency-20-bold" {...props}></Icon>
