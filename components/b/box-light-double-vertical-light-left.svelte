<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riqmprbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="riqmprbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-vertical-light-left" {...props}></Icon>
