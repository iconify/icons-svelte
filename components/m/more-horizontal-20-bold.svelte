<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz8a-28-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mz8a-28-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:more-horizontal-20-bold" {...props}></Icon>
