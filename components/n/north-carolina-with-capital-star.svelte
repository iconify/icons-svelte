<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2yej0b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e2yej0b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:north-carolina-with-capital-star" {...props}></Icon>
