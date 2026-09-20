<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr8cc2b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sr8cc2b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:dashboard" {...props}></Icon>
