<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_j7oubaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s_j7oubaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:product-catalog" {...props}></Icon>
