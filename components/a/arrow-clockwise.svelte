<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzy7cxw4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uzy7cxw4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-clockwise" {...props}></Icon>
