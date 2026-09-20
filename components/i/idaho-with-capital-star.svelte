<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn3q1p62s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hn3q1p62s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:idaho-with-capital-star" {...props}></Icon>
