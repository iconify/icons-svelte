<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9jc0ib3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="u9jc0ib3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:flag" {...props}></Icon>
