<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq3o_nbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="sq3o_nbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-dashed-vertical" {...props}></Icon>
