<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_9kv2fjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="b_9kv2fjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:eye-open" {...props}></Icon>
