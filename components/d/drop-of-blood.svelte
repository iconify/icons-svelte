<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlb-er9ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jlb-er9ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:drop-of-blood" {...props}></Icon>
