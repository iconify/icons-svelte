<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etzt6g6pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="etzt6g6pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:groovy" {...props}></Icon>
