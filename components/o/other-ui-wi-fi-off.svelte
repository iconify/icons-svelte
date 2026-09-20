<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh1x06b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eh1x06b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-wi-fi-off" {...props}></Icon>
