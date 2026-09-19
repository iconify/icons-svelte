<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvb6lmb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pvb6lmb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-counterclockwise" {...props}></Icon>
