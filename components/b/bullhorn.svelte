<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1nlpp2od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="o1nlpp2od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:bullhorn" {...props}></Icon>
