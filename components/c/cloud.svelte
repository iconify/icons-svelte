<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jru89b19c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jru89b19c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:cloud" {...props}></Icon>
