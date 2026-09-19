<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0mziyz2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="s0mziyz2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:p-square" {...props}></Icon>
