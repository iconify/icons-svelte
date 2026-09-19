<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4qybgd0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b4qybgd0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:handbag-fill" {...props}></Icon>
