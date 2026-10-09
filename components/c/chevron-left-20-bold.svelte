<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7xl99bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o7xl99bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-left-20-bold" {...props}></Icon>
