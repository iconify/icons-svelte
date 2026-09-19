<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bngpm7b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bngpm7b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-bar-up" {...props}></Icon>
