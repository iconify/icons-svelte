<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j28zcvwzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="j28zcvwzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:fire" {...props}></Icon>
