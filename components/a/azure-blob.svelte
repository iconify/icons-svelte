<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avsmaub8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":41.754,"height":48.143};
const content = `<path class="avsmaub8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:azure-blob" {...props}></Icon>
