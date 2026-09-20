<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch_5q9b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ch_5q9b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-up" {...props}></Icon>
