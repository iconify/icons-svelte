<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvcpefbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bvcpefbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:leaf-fill-16" {...props}></Icon>
