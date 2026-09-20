<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptp8j_z-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ptp8j_z-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:lodging" {...props}></Icon>
