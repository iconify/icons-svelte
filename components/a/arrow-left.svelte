<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp1l0fb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bp1l0fb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:arrow-left" {...props}></Icon>
