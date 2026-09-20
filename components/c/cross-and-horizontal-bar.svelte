<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx1giabeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lx1giabeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:cross-and-horizontal-bar" {...props}></Icon>
