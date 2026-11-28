<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmtqmcc6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zmtqmcc6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:restroom-thin" {...props}></Icon>
