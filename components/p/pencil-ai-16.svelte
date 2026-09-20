<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnmef8g9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pnmef8g9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pencil-ai-16" {...props}></Icon>
