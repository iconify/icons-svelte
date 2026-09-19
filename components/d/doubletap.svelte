<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8n9ys8jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="c8n9ys8jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:doubletap" {...props}></Icon>
