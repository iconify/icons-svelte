<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3-krgg1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a3-krgg1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:border-width" {...props}></Icon>
