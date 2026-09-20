<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7f-x89fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="x7f-x89fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-horizontal-stipple-left-up-right" {...props}></Icon>
