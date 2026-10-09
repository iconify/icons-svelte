<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rarcuc5bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rarcuc5bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:filter-20-bold" {...props}></Icon>
