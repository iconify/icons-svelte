<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flzzd6bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="flzzd6bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:recycling-container" {...props}></Icon>
