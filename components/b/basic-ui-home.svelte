<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olvbg8bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="olvbg8bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-home" {...props}></Icon>
