<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1-x7w-ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d1-x7w-ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:refresh-right" {...props}></Icon>
