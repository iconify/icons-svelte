<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrhi1zbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rrhi1zbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:idea-alt" {...props}></Icon>
