<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkc41lb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fkc41lb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-v" {...props}></Icon>
