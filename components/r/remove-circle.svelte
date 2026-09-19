<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1_emcbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="p1_emcbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:remove-circle" {...props}></Icon>
