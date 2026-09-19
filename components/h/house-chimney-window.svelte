<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9pq2-b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="b9pq2-b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:house-chimney-window" {...props}></Icon>
