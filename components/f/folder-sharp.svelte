<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4m17f5zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4m17f5zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:folder-sharp" {...props}></Icon>
