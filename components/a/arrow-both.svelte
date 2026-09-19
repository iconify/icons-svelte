<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0ie7db7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c0ie7db7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-both" {...props}></Icon>
