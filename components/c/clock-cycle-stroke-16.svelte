<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vioo8qbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vioo8qbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-cycle-stroke-16" {...props}></Icon>
