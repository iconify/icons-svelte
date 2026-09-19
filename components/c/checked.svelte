<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmah1zbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kmah1zbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:checked" {...props}></Icon>
