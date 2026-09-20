<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5286ob_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x5286ob_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:blender-dark" {...props}></Icon>
