<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-z5l41cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h-z5l41cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:defragment" {...props}></Icon>
