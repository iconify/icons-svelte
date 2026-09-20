<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixx7vz6ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixx7vz6ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connected" {...props}></Icon>
