<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e79veb9nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="e79veb9nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-down-right" {...props}></Icon>
