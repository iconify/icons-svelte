<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-j74pbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g-j74pbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chrome-close" {...props}></Icon>
