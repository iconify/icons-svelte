<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0hqintla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z0hqintla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:new-mexico" {...props}></Icon>
