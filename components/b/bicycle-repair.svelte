<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlyg5ji_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tlyg5ji_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bicycle-repair" {...props}></Icon>
