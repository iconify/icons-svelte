<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_10jfv9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="i_10jfv9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:cog" {...props}></Icon>
