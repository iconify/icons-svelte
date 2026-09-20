<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia7ydhbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ia7ydhbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:monitor" {...props}></Icon>
