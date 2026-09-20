<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7txlobxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p7txlobxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gl-inet" {...props}></Icon>
