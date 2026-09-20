<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zghiu7b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="zghiu7b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-round-down-right" {...props}></Icon>
