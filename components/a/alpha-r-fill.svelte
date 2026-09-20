<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl3c13s6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="vl3c13s6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-r-fill" {...props}></Icon>
