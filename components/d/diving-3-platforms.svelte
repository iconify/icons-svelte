<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ide58leqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ide58leqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:diving-3-platforms" {...props}></Icon>
