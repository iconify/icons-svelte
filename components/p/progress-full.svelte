<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqa938w4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oqa938w4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:progress-full" {...props}></Icon>
