<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn6np5bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vn6np5bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x3-16-solid" {...props}></Icon>
