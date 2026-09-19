<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji_0ycbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":832};
const content = `<path class="ji_0ycbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:origami" {...props}></Icon>
