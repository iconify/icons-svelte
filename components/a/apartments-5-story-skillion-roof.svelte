<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltq07achs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ltq07achs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-5-story-skillion-roof" {...props}></Icon>
