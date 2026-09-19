<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmbtl7v-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zmbtl7v-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:grid-3x3-stroke-16" {...props}></Icon>
