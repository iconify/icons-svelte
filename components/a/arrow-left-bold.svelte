<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erpo6qb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="erpo6qb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:arrow-left-bold" {...props}></Icon>
