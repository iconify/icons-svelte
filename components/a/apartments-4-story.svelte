<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkvyqmbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gkvyqmbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:apartments-4-story" {...props}></Icon>
