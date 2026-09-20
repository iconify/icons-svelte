<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlupp-6qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hlupp-6qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:honeycomb" {...props}></Icon>
