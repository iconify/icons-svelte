<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t94-lt9lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t94-lt9lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-arrows-transfer" {...props}></Icon>
