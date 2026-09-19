<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utpfh0bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="utpfh0bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-graph-down-left" {...props}></Icon>
