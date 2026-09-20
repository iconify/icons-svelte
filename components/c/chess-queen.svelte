<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f78rt7b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f78rt7b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chess-queen" {...props}></Icon>
