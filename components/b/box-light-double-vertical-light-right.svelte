<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxy8lcb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="oxy8lcb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-vertical-light-right" {...props}></Icon>
