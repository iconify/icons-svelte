<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc5q4acph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nc5q4acph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:raphael" {...props}></Icon>
