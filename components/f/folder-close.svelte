<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8f4i2m7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="j8f4i2m7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:folder-close" {...props}></Icon>
