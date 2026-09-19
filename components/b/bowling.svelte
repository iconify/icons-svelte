<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1774m7wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y1774m7wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bowling" {...props}></Icon>
