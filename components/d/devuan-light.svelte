<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eev7bvb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eev7bvb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:devuan-light" {...props}></Icon>
