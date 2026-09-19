<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq-6cee7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xq-6cee7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:globe" {...props}></Icon>
