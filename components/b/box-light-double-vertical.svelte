<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy5g19brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hy5g19brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-vertical" {...props}></Icon>
