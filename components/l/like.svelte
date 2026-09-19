<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-3au3dcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="x-3au3dcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:like" {...props}></Icon>
