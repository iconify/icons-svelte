<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t22-p6_ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t22-p6_ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bowling-ball" {...props}></Icon>
