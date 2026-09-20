<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9t5p3b5c.css';
import '../../css/o/ohfe1ob8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="p9t5p3b5c"/><path class="ohfe1ob8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:image" {...props}></Icon>
