<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlkgi9b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="vlkgi9b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chevron-right" {...props}></Icon>
