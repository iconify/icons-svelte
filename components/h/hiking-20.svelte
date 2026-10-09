<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5-tgpcat.css';
import '../../css/a/a3mz8kb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y5-tgpcat"/><path class="a3mz8kb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hiking-20" {...props}></Icon>
