<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thmpixb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="thmpixb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:cc" {...props}></Icon>
