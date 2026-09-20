<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvpm8dayr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xvpm8dayr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:definition-search-book" {...props}></Icon>
