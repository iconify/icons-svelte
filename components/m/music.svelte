<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8kdn0ytq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n8kdn0ytq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:music" {...props}></Icon>
