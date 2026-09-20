<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vczdkt4km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="vczdkt4km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-a" {...props}></Icon>
