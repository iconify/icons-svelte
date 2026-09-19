<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml2bg2b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ml2bg2b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-right-circle" {...props}></Icon>
