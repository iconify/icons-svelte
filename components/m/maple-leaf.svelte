<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv57wib5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dv57wib5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:maple-leaf" {...props}></Icon>
