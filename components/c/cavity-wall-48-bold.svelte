<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcllyhbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dcllyhbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cavity-wall-48-bold" {...props}></Icon>
