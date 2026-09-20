<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8av0dbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="v8av0dbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-dashed-right" {...props}></Icon>
