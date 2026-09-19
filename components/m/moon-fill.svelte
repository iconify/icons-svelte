<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meg5cxbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="meg5cxbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:moon-fill" {...props}></Icon>
