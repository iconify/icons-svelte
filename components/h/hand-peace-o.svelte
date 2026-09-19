<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czb3gi03f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="czb3gi03f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hand-peace-o" {...props}></Icon>
