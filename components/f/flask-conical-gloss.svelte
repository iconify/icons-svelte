<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-6qxlb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-6qxlb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flask-conical-gloss" {...props}></Icon>
