<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_fay6bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p_fay6bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:arrow-down-right-mirrored-8" {...props}></Icon>
