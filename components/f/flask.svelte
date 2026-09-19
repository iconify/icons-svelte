<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srr2jxk_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="srr2jxk_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:flask" {...props}></Icon>
