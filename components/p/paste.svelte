<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arc1umbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="arc1umbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:paste" {...props}></Icon>
