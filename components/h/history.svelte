<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqz_8mb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jqz_8mb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:history" {...props}></Icon>
