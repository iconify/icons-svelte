<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnx13n9nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jnx13n9nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:grid-horizontal" {...props}></Icon>
