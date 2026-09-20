<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px5cveb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="px5cveb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-both-16" {...props}></Icon>
