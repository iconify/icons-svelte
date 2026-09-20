<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxix1zkta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jxix1zkta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-up-right-stipple-inner" {...props}></Icon>
