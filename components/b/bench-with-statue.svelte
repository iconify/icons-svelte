<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq-tlin1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aq-tlin1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bench-with-statue" {...props}></Icon>
