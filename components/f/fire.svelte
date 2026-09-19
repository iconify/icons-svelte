<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blf-jfb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="blf-jfb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:fire" {...props}></Icon>
