<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh5vy0b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="eh5vy0b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:checked" {...props}></Icon>
