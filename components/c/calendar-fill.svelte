<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw6szvbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zw6szvbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar-fill" {...props}></Icon>
