<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgprs5nyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fgprs5nyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-down-left-circle" {...props}></Icon>
