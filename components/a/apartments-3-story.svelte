<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srlzd6bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="srlzd6bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-3-story" {...props}></Icon>
