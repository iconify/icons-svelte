<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejo68-63n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ejo68-63n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:rotateclockwise" {...props}></Icon>
