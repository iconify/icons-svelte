<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu8s5r7ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mu8s5r7ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:building-part" {...props}></Icon>
