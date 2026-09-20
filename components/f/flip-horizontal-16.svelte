<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilyhpi0vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ilyhpi0vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:flip-horizontal-16" {...props}></Icon>
