<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz5-qd-5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bz5-qd-5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:netherlands-with-capital-star" {...props}></Icon>
