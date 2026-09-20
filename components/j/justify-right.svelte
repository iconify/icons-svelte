<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru5ry8blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ru5ry8blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:justify-right" {...props}></Icon>
