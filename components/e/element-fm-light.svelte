<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0g67cc2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0g67cc2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:element-fm-light" {...props}></Icon>
