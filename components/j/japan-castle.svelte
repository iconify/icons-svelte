<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgg0w59fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cgg0w59fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:japan-castle" {...props}></Icon>
