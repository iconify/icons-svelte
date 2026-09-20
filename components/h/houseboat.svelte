<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hinn72boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hinn72boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:houseboat" {...props}></Icon>
