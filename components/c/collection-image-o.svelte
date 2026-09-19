<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe3j6tb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="qe3j6tb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-image-o" {...props}></Icon>
