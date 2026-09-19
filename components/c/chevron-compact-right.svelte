<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msmt2ql3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="msmt2ql3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-compact-right" {...props}></Icon>
