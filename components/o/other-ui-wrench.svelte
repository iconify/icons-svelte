<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ws2cc4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p7ws2cc4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-wrench" {...props}></Icon>
