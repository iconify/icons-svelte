<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osvwi8b0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="osvwi8b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:madagascar-with-capital-star" {...props}></Icon>
