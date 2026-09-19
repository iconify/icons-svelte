<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7om_9bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b7om_9bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:crop-alt" {...props}></Icon>
