<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0huf36pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="r0huf36pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-m-fill" {...props}></Icon>
