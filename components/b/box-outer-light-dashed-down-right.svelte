<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-8blkbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="i-8blkbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-dashed-down-right" {...props}></Icon>
