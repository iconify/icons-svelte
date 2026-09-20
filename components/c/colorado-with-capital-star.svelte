<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yimt7bc-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yimt7bc-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:colorado-with-capital-star" {...props}></Icon>
