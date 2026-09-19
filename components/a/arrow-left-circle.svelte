<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6eiweb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k6eiweb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-left-circle" {...props}></Icon>
