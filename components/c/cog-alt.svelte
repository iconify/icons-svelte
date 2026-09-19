<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkca6ac2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rkca6ac2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:cog-alt" {...props}></Icon>
